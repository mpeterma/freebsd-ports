# Created by: Matthias Petermann <matthias@petermann-it.de>
# $FreeBSD: head/german/trytond_account_de_skr03/Makefile 371202 2014-10-19 17:45:13Z mva $

PORTNAME=	trytond_account_de_skr03
PORTVERSION=	2.4.0
PORTREVISION=	1
CATEGORIES=	german finance python
MASTER_SITES=	http://downloads.tryton.org/${PORTVERSION:R}/

MAINTAINER=	matthias@petermann.it
COMMENT=	Tryton Application Platform (German Account Chart)

LICENSE=	GPLv3

RUN_DEPENDS=	trytond>=2.4.0:${PORTSDIR}/finance/trytond \
		trytond_account>=2.4.1:${PORTSDIR}/finance/trytond_account

CONFLICTS=	trytond28_account_de_skr03-2.8.*

USES=		python
USE_PYTHON=	distutils autoplist

.include <bsd.port.mk>
