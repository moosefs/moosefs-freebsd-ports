# Created by: Jakub Kruszona-Zawadzki <acid@moosefs.com> ; Based on port created by: Chifeng Qu <chifeng@gmail.com>
# $FreeBSD: head/sysutils/moosefs3-client/Makefile 419134 2016-07-26 16:56:05Z feld $

PKGNAMESUFFIX=	-client

COMMENT=	MooseFS client tools

LICENSE=	GPLv2

MFS_COMPONENT=	client

BROKEN_powerpc64=	fails to compile: mfs_fuse.c: internal compiler error: Segmentation fault

MASTERDIR=	${.CURDIR}/../moosefs3-master

.include "${MASTERDIR}/Makefile"
