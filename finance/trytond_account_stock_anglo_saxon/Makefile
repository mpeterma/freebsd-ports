# Created by: Matthias Petermann <matthias@petermann-it.de>
# $FreeBSD: head/finance/trytond_account_stock_anglo_saxon/Makefile 371284 2014-10-20 17:18:18Z mva $

PORTNAME=	trytond_account_stock_anglo_saxon
PORTVERSION=	2.4.5
PORTREVISION=	1
CATEGORIES=	finance python
MASTER_SITES=	http://downloads.tryton.org/${PORTVERSION:R}/

MAINTAINER=	matthias@petermann-it.de
COMMENT=	Tryton Application Platform (Account Stock Anglo Saxon Module)

LICENSE=	GPLv3

RUN_DEPENDS=	trytond>=2.4.0:${PORTSDIR}/finance/trytond \
		trytond_account_invoice>=2.4.1:${PORTSDIR}/finance/trytond_account_invoice \
		trytond_account_stock_continental>=2.4.1:${PORTSDIR}/finance/trytond_account_stock_continental

CONFLICTS=	trytond28_account_stock_anglo_saxon-2.8.*

USES=		python
USE_PYTHON=	distutils autoplist

.include <bsd.port.mk>
