PORTNAME=	pam_hwasly
PORTVERSION=	19.1.3
CATEGORIES=	sysutils

MAINTAINER=	ad@hwasly.org
COMMENT=	HWasly shared authentication system using PAM

LICENSE=	BSD2CLAUSE

USE_GITHUB=	yes
GH_ACCOUNT=	hwasly

post-stage:
	${RM} ${STAGEDIR}${PREFIX}/lib/*.a

.include <bsd.port.mk>
