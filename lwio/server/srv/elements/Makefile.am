noinst_LTLIBRARIES = libsrvelements.la

libsrvelements_la_SOURCES = \
    context.c       \
    globals.c       \
    libmain.c       \
    resources.c     \
    srvasyncstate.c \
    srvconnection.c \
    srvfile.c       \
    srvfile2.c      \
    srvfinder.c     \
    srvgss.c        \
    srvioapi.c      \
    srvsession.c    \
    srvsession2.c   \
    srvtimer.c      \
    srvtree.c       \
    srvtree2.c

libsrvelements_la_CPPFLAGS = \
    -DLW_ENABLE_THREADS=1  \
    -I@top_srcdir@         \
    -I@top_srcdir@/include \
    -I@top_srcdir@/server/include \
    -I@top_srcdir@/server/srv/include

libsrvelements_la_LDFLAGS = -static

