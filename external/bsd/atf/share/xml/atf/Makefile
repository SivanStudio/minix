# $NetBSD: Makefile,v 1.3 2010/06/04 08:33:41 jmmv Exp $

.include <bsd.own.mk>

.if ${MKSHARE} != "no"
SRCDIR=		${NETBSDSRCDIR}/external/bsd/atf/dist
.PATH:		${SRCDIR}/atf-report

FILESDIR=	/usr/share/xml/atf
FILESMODE=	444
FILES=		tests-results.dtd
.endif

.include <bsd.prog.mk>
