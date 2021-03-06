# $FreeBSD$

PORTNAME=	Products.PlacelessTranslationService
PORTVERSION=	2.0.5
PORTREVISION=	2
CATEGORIES=	devel python zope
MASTER_SITES=	CHEESESHOP
PKGNAMEPREFIX=	${PYTHON_PKGNAMEPREFIX}
DIST_SUBDIR=	zope

MAINTAINER=	zope@FreeBSD.org
COMMENT=	Internationalizing and localizing software for Zope 2

LICENSE=	GPLv2

RUN_DEPENDS=	${PYTHON_PKGNAMEPREFIX}python-gettext>0:textproc/py-python-gettext \
		${PYTHON_PKGNAMEPREFIX}zope.annotation>=0:devel/py-zope.annotation \
		${PYTHON_PKGNAMEPREFIX}zope.component>=0:devel/py-zope.component \
		${PYTHON_PKGNAMEPREFIX}zope.deferredimport>=0:devel/py-zope.deferredimport \
		${PYTHON_PKGNAMEPREFIX}zope.deprecation>=0:devel/py-zope.deprecation \
		${PYTHON_PKGNAMEPREFIX}zope.i18n>=0:devel/py-zope.i18n \
		${PYTHON_PKGNAMEPREFIX}zope.interface>=0:devel/py-zope.interface \
		${PYTHON_PKGNAMEPREFIX}zope.publisher>=0:devel/py-zope.publisher \
		${PYTHON_PKGNAMEPREFIX}Acquisition>=0:devel/py-Acquisition \
		${PYTHON_PKGNAMEPREFIX}DateTime>=0:devel/py-DateTime \
		${PYTHON_PKGNAMEPREFIX}ExtensionClass>=0:devel/py-ExtensionClass \
		zodb${PYTHON_PKGNAMESUFFIX}>=0:databases/zodb3

USES=		python shebangfix zip
USE_PYTHON=	autoplist distutils
SHEBANG_FILES=	Products/PlacelessTranslationService/bin/convertToLocales.py

.include <bsd.port.mk>
