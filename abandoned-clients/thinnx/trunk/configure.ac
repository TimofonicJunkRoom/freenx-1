dnl Process this file with autoconf to produce a configure script.

AC_INIT(thinnx/thinnx.c)
dnl Every other copy of the package version number gets its value from here
AM_INIT_AUTOMAKE(thinnx, 0.1.0)

dnl create a config.h file (Automake will add -DHAVE_CONFIG_H)
AM_CONFIG_HEADER(config.h)

AC_SUBST(VERSION)

ISODATE=`date +%Y-%m-%d`
AC_SUBST(ISODATE)

AC_CANONICAL_HOST

dnl Checks for programs.
AC_PROG_INSTALL
AC_PROG_CC

dnl Checks for libraries.
AM_PATH_GTK(1.2.0,, AC_MSG_ERROR(Can't find GTK+ 1.2 or better))

dnl Checks for header files.
AC_HEADER_STDC
AC_CHECK_HEADERS(unistd.h sys/param.h sys/time.h time.h sys/mkdev.h sys/sysmacros.h string.h memory.h fcntl.h dirent.h sys/ndir.h ndir.h alloca.h locale.h )

AC_HEADER_MAJOR

dnl Checks for typedefs, structures, and compiler characteristics.

dnl Checks for library functions.

AC_OUTPUT(Makefile m4/Makefile thinnx/Makefile)
