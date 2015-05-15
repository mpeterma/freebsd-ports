# Created by: Matthias Petermann <matthias@petermann-it.de>
# $FreeBSD: head/finance/trytond_stock_forecast/Makefile 371284 2014-10-20 17:18:18Z mva $

PORTNAME=	trytond_stock_forecast
PORTVERSION=	2.4.1
PORTREVISION=	1
CATEGORIES=	finance python
MASTER_SITES=	http://downloads.tryton.org/${PORTVERSION:R}/

MAINTAINER=	matthias@petermann-it.de
COMMENT=	Tryton Application Platform (Stock Forecast Module)

LICENSE=	GPLv3

RUN_DEPENDS=	${PYTHON_PKGNAMEPREFIX}dateutil>=1.5:${PORTSDIR}/devel/py-dateutil \
		trytond>=2.4.0:${PORTSDIR}/finance/trytond \
		trytond_product>=2.4.0:${PORTSDIR}/finance/trytond_product \
		trytond_stock>=2.4.0:${PORTSDIR}/finance/trytond_stock \
		trytond_company>=2.4.0:${PORTSDIR}/finance/trytond_company

CONFLICTS=	trytond28_stock_forecast-2.8.*

USES=		python
USE_PYTHON=	distutils autoplist

.include <bsd.port.mk>
