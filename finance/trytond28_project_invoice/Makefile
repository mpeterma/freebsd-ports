# Created by: Matthias Petermann <matthias@petermann-it.de>
# $FreeBSD: head/finance/trytond28_project_invoice/Makefile 380744 2015-03-08 09:42:52Z rm $

PORTNAME=	trytond28_project_invoice
PORTVERSION=	2.8.3
CATEGORIES=	finance python
MASTER_SITES=	CHEESESHOP \
		http://downloads.tryton.org/${PORTVERSION:R}/
DISTNAME=	trytond_project_invoice-${PORTVERSION}

MAINTAINER=	matthias@petermann-it.de
COMMENT=	Tryton Application Platform (Project Invoice Module)

LICENSE=	GPLv3

RUN_DEPENDS=	trytond28_timesheet>=2.8.0:${PORTSDIR}/finance/trytond28_timesheet \
		trytond28_project_revenue>=2.8.0:${PORTSDIR}/finance/trytond28_project_revenue \
		trytond28_account_invoice>=2.8.2:${PORTSDIR}/finance/trytond28_account_invoice \
		trytond28_product>=2.8.0:${PORTSDIR}/finance/trytond28_product

CONFLICTS=	trytond_project_invoice-2.[46].*

USES=		python
USE_PYTHON=	distutils autoplist

.include <bsd.port.mk>
