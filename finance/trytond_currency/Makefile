# Created by: Matthias Petermann <matthias@petermann-it.de>
# $FreeBSD: head/finance/trytond_currency/Makefile 371284 2014-10-20 17:18:18Z mva $

PORTNAME=	trytond_currency
PORTVERSION=	2.4.0
PORTREVISION=	1
CATEGORIES=	finance python
MASTER_SITES=	http://downloads.tryton.org/${PORTVERSION:R}/

MAINTAINER=	matthias@petermann.it
COMMENT=	Tryton Application Platform (Currency Module)

LICENSE=	GPLv3

RUN_DEPENDS=	trytond>=2.4.0:${PORTSDIR}/finance/trytond

CONFLICTS=	trytond28_currency-2.8.*

USES=		python
USE_PYTHON=	distutils autoplist

.include <bsd.port.mk>
