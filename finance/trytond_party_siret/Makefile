# Created by: Matthias Petermann <matthias@petermann-it.de>
# $FreeBSD: head/finance/trytond_party_siret/Makefile 371284 2014-10-20 17:18:18Z mva $

PORTNAME=	trytond_party_siret
PORTVERSION=	2.4.1
PORTREVISION=	1
CATEGORIES=	finance python
MASTER_SITES=	http://downloads.tryton.org/${PORTVERSION:R}/

MAINTAINER=	matthias@petermann.it
COMMENT=	Tryton Application Platform (Party Siret Module)

LICENSE=	GPLv3

RUN_DEPENDS=	trytond>=2.4.0:${PORTSDIR}/finance/trytond \
		trytond_party>=2.4.0:${PORTSDIR}/finance/trytond_party

CONFLICTS=	trytond28_party_siret-2.8.*

USES=		python
USE_PYTHON=	distutils autoplist

.include <bsd.port.mk>
