# Created by: Matthias Petermann <matthias@petermann-it.de>
# $FreeBSD: head/finance/trytond_account_invoice_history/Makefile 371284 2014-10-20 17:18:18Z mva $

PORTNAME=	trytond_account_invoice_history
PORTVERSION=	2.4.2
PORTREVISION=	1
CATEGORIES=	finance python
MASTER_SITES=	http://downloads.tryton.org/${PORTVERSION:R}/

MAINTAINER=	matthias@petermann.it
COMMENT=	Tryton Application Platform (Account Invoice History Module)

LICENSE=	GPLv3

RUN_DEPENDS=	trytond>=2.4.0:${PORTSDIR}/finance/trytond \
		trytond_account_invoice>=2.4.1:${PORTSDIR}/finance/trytond_account_invoice

CONFLICTS=	trytond28_account_invoice_history-2.8.*

USES=		python
USE_PYTHON=	distutils autoplist

.include <bsd.port.mk>
