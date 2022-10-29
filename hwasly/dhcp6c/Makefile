PORTNAME=	dhcp6c
PORTREVISION=	1 # GH_TAGNAME
DISTVERSION=	20200512
DISTVERSIONPREFIX=v
CATEGORIES=	net

MAINTAINER=	franco@hwasly.org
COMMENT=	HWasly WIDE-DHCPv6 client
WWW=		https://github.com/hwasly/dhcp6c/

LICENSE=	BSD3CLAUSE
LICENSE_FILE=	${WRKSRC}/COPYRIGHT

CONFLICTS_INSTALL=	dhcp6

USE_GITHUB=	yes
GH_ACCOUNT=	hwasly
GH_TAGNAME=	cff2641

GNU_CONFIGURE=	yes
CONFIGURE_ARGS=	--sysconfdir=${LOCALBASE}/etc \
		--with-localdbdir=/var/db
USE_RC_SUBR=	dhcp6c

post-install:
	${INSTALL_DATA} ${WRKSRC}/dhcp6c.conf.sample ${STAGEDIR}${PREFIX}/etc

.include <bsd.port.mk>
