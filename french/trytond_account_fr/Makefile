# Created by: Matthias Petermann <matthias@petermann-it.de>
# $FreeBSD: head/french/trytond_account_fr/Makefile 371201 2014-10-19 17:18:24Z mva $

PORTNAME=	trytond_account_fr
PORTVERSION=	2.4.0
PORTREVISION=	1
CATEGORIES=	french finance python
MASTER_SITES=	http://downloads.tryton.org/${PORTVERSION:R}/

MAINTAINER=	matthias@petermann.it
COMMENT=	Tryton Application Platform (French Account Chart)

LICENSE=	GPLv3

RUN_DEPENDS=	trytond>=2.4.0:${PORTSDIR}/finance/trytond \
		trytond_account>=2.4.1:${PORTSDIR}/finance/trytond_account

CONFLICTS=	trytond28_account_fr-2.8.*

USES=		python
USE_PYTHON=	distutils autoplist

.include <bsd.port.mk>
