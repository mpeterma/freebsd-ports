# Created by: Matthias Petermann <matthias@petermann-it.de>
# $FreeBSD: head/finance/trytond28_stock_supply_forecast/Makefile 371284 2014-10-20 17:18:18Z mva $

PORTNAME=	trytond28_stock_supply_forecast
PORTVERSION=	2.8.0
PORTREVISION=	1
CATEGORIES=	finance python
MASTER_SITES=	https://pypi.python.org/packages/source/t/trytond_stock_supply_forecast/ \
		http://downloads.tryton.org/${PORTVERSION:R}/
DISTNAME=	trytond_stock_supply_forecast-${PORTVERSION}

MAINTAINER=	matthias@petermann-it.de
COMMENT=	Tryton Application Platform (Stock Supply Forecast Module)

LICENSE=	GPLv3

RUN_DEPENDS=	trytond28_stock_supply>=2.8.1:${PORTSDIR}/finance/trytond28_stock_supply \
		trytond28_stock_forecast>=2.8.0:${PORTSDIR}/finance/trytond28_stock_forecast

CONFLICTS=	trytond_stock_supply_forecast-2.[46].*

USES=		python
USE_PYTHON=	distutils autoplist

.include <bsd.port.mk>
