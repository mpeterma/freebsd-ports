# Created by: Matthias Petermann <matthias@petermann-it.de>
# $FreeBSD: head/finance/trytond28_country/Makefile 380744 2015-03-08 09:42:52Z rm $

PORTNAME=	trytond28_country
PORTVERSION=	2.8.1
CATEGORIES=	finance python
MASTER_SITES=	CHEESESHOP \
		http://downloads.tryton.org/${PORTVERSION:R}/
DISTNAME=	trytond_country-${PORTVERSION}

MAINTAINER=	matthias@petermann-it.de
COMMENT=	Tryton Application Platform (Country Module)

LICENSE=	GPLv3

RUN_DEPENDS=	trytond28>=2.8.2:${PORTSDIR}/finance/trytond28

CONFLICTS=	trytond_country-2.[46].*

USES=		python
USE_PYTHON=	distutils autoplist

.include <bsd.port.mk>
