# Created by: Matthias Petermann <matthias@petermann-it.de>
# $FreeBSD: head/finance/trytond_stock_supply_production/Makefile 371284 2014-10-20 17:18:18Z mva $

PORTNAME=	trytond_stock_supply_production
PORTVERSION=	2.4.2
PORTREVISION=	1
CATEGORIES=	finance python
MASTER_SITES=	http://downloads.tryton.org/${PORTVERSION:R}/

MAINTAINER=	matthias@petermann.it
COMMENT=	Tryton Application Platform (Stock Supply Production Module)

LICENSE=	GPLv3

RUN_DEPENDS=	trytond>=2.4.0:${PORTSDIR}/finance/trytond \
		trytond_stock_supply>=2.4.0:${PORTSDIR}/finance/trytond_stock_supply \
		trytond_product>=2.4.0:${PORTSDIR}/finance/trytond_product

CONFLICTS=	trytond28_stock_supply_production-2.8.*

USES=		python
USE_PYTHON=	distutils autoplist

.include <bsd.port.mk>
