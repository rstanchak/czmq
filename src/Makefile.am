#################################################################
#   GENERATED SOURCE CODE, DO NOT EDIT EXCEPT EXPERIMENTALLY    #
#   Please read the README.txt file in the model directory.     #
#################################################################
lib_LTLIBRARIES = libczmq.la

pkgconfigdir = $(libdir)/pkgconfig
pkgconfig_DATA = libczmq.pc

include_HEADERS = \
    ../include/czmq.h \
    ../include/czmq/czmq_prelude.h \
    ../include/czmq/zactor.h \
    ../include/czmq/zauth.h \
    ../include/czmq/zbeacon.h \
    ../include/czmq/zcert.h \
    ../include/czmq/zcertstore.h \
    ../include/czmq/zchunk.h \
    ../include/czmq/zclock.h \
    ../include/czmq/zconfig.h \
    ../include/czmq/zdigest.h \
    ../include/czmq/zdir.h \
    ../include/czmq/zdir_patch.h \
    ../include/czmq/zfile.h \
    ../include/czmq/zframe.h \
    ../include/czmq/zhash.h \
    ../include/czmq/zgossip.h \
    ../include/czmq/zlist.h \
    ../include/czmq/zloop.h \
    ../include/czmq/zmsg.h \
    ../include/czmq/zpoller.h \
    ../include/czmq/zproxy.h \
    ../include/czmq/zrex.h \
    ../include/czmq/zsock.h \
    ../include/czmq/zsock_monitor.h \
    ../include/czmq/zsock_option.h \
    ../include/czmq/zstr.h \
    ../include/czmq/zsys.h \
    ../include/czmq/zuuid.h \
    zgossip_msg.h \
    ../include/czmq/zctx.h \
    ../include/czmq/zmonitor.h \
    ../include/czmq/zmutex.h \
    ../include/czmq/zsocket.h \
    ../include/czmq/zsockopt.h \
    ../include/czmq/zthread.h

libczmq_la_SOURCES = \
    platform.h \
    zactor.c \
    zauth.c \
    zbeacon.c \
    zcert.c \
    zcertstore.c \
    zchunk.c \
    zclock.c \
    zconfig.c \
    zdigest.c \
    zdir.c \
    zdir_patch.c \
    zfile.c \
    zframe.c \
    zhash.c \
    zgossip.c \
    zlist.c \
    zloop.c \
    zmsg.c \
    zpoller.c \
    zproxy.c \
    zrex.c \
    zsock.c \
    zsock_monitor.c \
    zsock_option.c \
    zstr.c \
    zsys.c \
    zuuid.c \
    zgossip_msg.c \
    zctx.c \
    zmonitor.c \
    zmutex.c \
    zsocket.c \
    zsockopt.c \
    zthread.c

AM_CFLAGS = -g
AM_CPPFLAGS = -I$(top_srcdir)/include
bin_PROGRAMS = czmq_selftest
czmq_selftest_LDADD = libczmq.la
czmq_selftest_SOURCES = czmq_selftest.c

if ON_MINGW
libczmq_la_LDFLAGS = -no-undefined -avoid-version -version-info @LTVER@
else
libczmq_la_LDFLAGS = -version-info @LTVER@
endif

TESTS = czmq_selftest

# Produce generated models; do this manually in src directory
code:
	gsl -q sockopts.xml
	gsl -q zgossip.xml
	gsl -q zgossip_msg.xml

#################################################################
#   GENERATED SOURCE CODE, DO NOT EDIT EXCEPT EXPERIMENTALLY    #
#   Please read the README.txt file in the model directory.     #
#################################################################
