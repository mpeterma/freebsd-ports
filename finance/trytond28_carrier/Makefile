# Created by: Matthias Petermann <matthias@petermann-it.de>
# $FreeBSD: head/finance/trytond28_carrier/Makefile 371284 2014-10-20 17:18:18Z mva $

PORTNAME=	trytond28_carrier
PORTVERSION=	2.8.0
PORTREVISION=	1
CATEGORIES=	finance python
MASTER_SITES=	https://pypi.python.org/packages/source/t/trytond_carrier/ \
		http://downloads.tryton.org/${PORTVERSION:R}/
DISTNAME=	trytond_carrier-${PORTVERSION}

MAINTAINER=	matthias@petermann-it.de
COMMENT=	Tryton Application Platform (Carrier Module)

LICENSE=	GPLv3

RUN_DEPENDS=	trytond28_party>=2.8.0:${PORTSDIR}/finance/trytond28_party \
		trytond28_product>=2.8.0:${PORTSDIR}/finance/trytond28_product

CONFLICTS=	trytond_carrier-2.[46].*

USES=		python
USE_PYTHON=	distutils autoplist

.include <bsd.port.mk>
