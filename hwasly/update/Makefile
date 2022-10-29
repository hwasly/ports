PORTNAME=	update
PORTVERSION=	22.7.5
CATEGORIES=	sysutils
PKGNAMEPREFIX=	${GH_ACCOUNT}-

MAINTAINER=	franco@hwasly.org
COMMENT=	HWasly update utilities
WWW=		https://hwasly.org/

LICENSE=	BSD2CLAUSE

LIB_DEPENDS+=	libucl.so:textproc/libucl

USES=		ssl

MAKE_ENV=	UPDATE_RELEASE=${PORTVERSION}

USE_GITHUB=	yes
GH_ACCOUNT=	${CATEGORIES:[1]}
GH_TAGNAME=	b3bf3f4

.include <bsd.port.mk>
