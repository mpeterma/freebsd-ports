# Created by: Matthias Petermann <matthias@petermann-it.de>
# $FreeBSD: head/finance/trytond_project_revenue/Makefile 371284 2014-10-20 17:18:18Z mva $

PORTNAME=	trytond_project_revenue
PORTVERSION=	2.4.1
PORTREVISION=	1
CATEGORIES=	finance python
MASTER_SITES=	http://downloads.tryton.org/${PORTVERSION:R}/

MAINTAINER=	matthias@petermann.it
COMMENT=	Tryton Application Platform (Project Revenue Module)

LICENSE=	GPLv3

RUN_DEPENDS=	trytond>=2.4.0:${PORTSDIR}/finance/trytond \
		trytond_project>=2.4.0:${PORTSDIR}/finance/trytond_project \
		trytond_product>=2.4.0:${PORTSDIR}/finance/trytond_product

CONFLICTS=	trytond28_project_revenue-2.8.*

USES=		python
USE_PYTHON=	distutils autoplist

.include <bsd.port.mk>
