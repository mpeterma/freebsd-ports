# Created by: Matthias Petermann <matthias@petermann-it.de>
# $FreeBSD: head/finance/trytond28_project/Makefile 380744 2015-03-08 09:42:52Z rm $

PORTNAME=	trytond28_project
PORTVERSION=	2.8.1
CATEGORIES=	finance python
MASTER_SITES=	CHEESESHOP \
		http://downloads.tryton.org/${PORTVERSION:R}/
DISTNAME=	trytond_project-${PORTVERSION}

MAINTAINER=	matthias@petermann-it.de
COMMENT=	Tryton Application Platform (Project Module)

LICENSE=	GPLv3

RUN_DEPENDS=	trytond28>=2.8.2:${PORTSDIR}/finance/trytond28 \
		trytond28_timesheet>=2.8.0:${PORTSDIR}/finance/trytond28_timesheet \
		trytond28_party>=2.8.0:${PORTSDIR}/finance/trytond28_party

CONFLICTS=	trytond_project-2.[46].*

USES=		python
USE_PYTHON=	distutils autoplist

.include <bsd.port.mk>
