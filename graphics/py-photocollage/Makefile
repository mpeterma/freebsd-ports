# Created by: Matthias Petermann <matthias@petermann-it.de>
# $FreeBSD$

PORTNAME=	photocollage
PORTVERSION=	1.3.0.20150514
CATEGORIES=	graphics python

MAINTAINER=	matthias@petermann-it.de
COMMENT=	Graphical tool to make photo collage posters

LICENSE=	GPLv2

RUN_DEPENDS=	${PYTHON_PKGNAMEPREFIX}cairo>=1.10.0:${PORTSDIR}/graphics/py-cairo

USE_GITHUB=	yes
GH_ACCOUNT=	adrienverge
GH_PROJECT=	PhotoCollage
GH_TAGNAME=	98f9b4f

USES=		gettext python
USE_PYTHON=	distutils autoplist
USE_GNOME=	gtk20 pygtk2

.include <bsd.port.mk>
