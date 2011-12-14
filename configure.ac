AC_INIT([redsocks], [0.3])
AC_PREREQ([2.59])
AM_INIT_AUTOMAKE([1.10 no-define])
AC_CONFIG_HEADERS([config.h])
AC_DEFINE([USE_IPTABLES], [],[Use iptables on Linux]) # or define USE_PF to use pf on OpenBSD
AC_PROG_CC
AC_CONFIG_FILES([Makefile])
AC_CHECK_LIB([event], [event_init], ,AC_MSG_ERROR([Unable to find libevent2]))
AC_OUTPUT
