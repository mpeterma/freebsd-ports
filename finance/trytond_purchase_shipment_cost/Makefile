# Created by: Matthias Petermann <matthias@petermann-it.de>
# $FreeBSD: head/finance/trytond_purchase_shipment_cost/Makefile 371284 2014-10-20 17:18:18Z mva $

PORTNAME=	trytond_purchase_shipment_cost
PORTVERSION=	2.4.2
PORTREVISION=	1
CATEGORIES=	finance python
MASTER_SITES=	http://downloads.tryton.org/${PORTVERSION:R}/

MAINTAINER=	matthias@petermann-it.de
COMMENT=	Tryton Application Platform (Purchase Shipment Cost Module)

LICENSE=	GPLv3

RUN_DEPENDS=	trytond>=2.4.0:${PORTSDIR}/finance/trytond \
		trytond_carrier>=2.4.1:${PORTSDIR}/finance/trytond_carrier \
		trytond_currency>=2.4.0:${PORTSDIR}/finance/trytond_currency \
		trytond_stock>=2.4.0:${PORTSDIR}/finance/trytond_stock

CONFLICTS=	trytond28_purchase_shipment_cost-2.8.*

USES=		python
USE_PYTHON=	distutils autoplist

.include <bsd.port.mk>
