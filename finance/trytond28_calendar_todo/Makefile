# Created by: Matthias Petermann <matthias@petermann-it.de>
# $FreeBSD: head/finance/trytond28_calendar_todo/Makefile 380744 2015-03-08 09:42:52Z rm $

PORTNAME=	trytond28_calendar_todo
PORTVERSION=	2.8.1
CATEGORIES=	finance python
MASTER_SITES=	CHEESESHOP \
		http://downloads.tryton.org/${PORTVERSION:R}/
DISTNAME=	trytond_calendar_todo-${PORTVERSION}

MAINTAINER=	matthias@petermann-it.de
COMMENT=	Tryton Application Platform (Calendar Todo Module)

LICENSE=	GPLv3

RUN_DEPENDS=	trytond28_calendar>=2.8.0:${PORTSDIR}/finance/trytond28_calendar

CONFLICTS=	trytond_calendar_todo-2.[46].*

USES=		python
USE_PYTHON=	distutils autoplist

.include <bsd.port.mk>
