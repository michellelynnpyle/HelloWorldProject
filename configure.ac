AC_INIT([myfirstproject], [0.01], [michellepyle@gmail.com], [hello])
# force version of autoconf
AC_PREREQ([2.68])
# check for source file
AC_CONFIG_SRCDIR([hello.c])
# where to place configuration results
AC_CONFIG_HEADERS([config.h])
# make a place for auxillary files
AC_CONFIG_AUX_DIR([build-aux])

# enable automake to create makefiles
AM_INIT_AUTOMAKE([1.11 -Wall -Werror])
AC_CONFIG_FILES([Makefile])

# look for the c compiler
AC_PROG_CC

# do final output
AC_OUTPUT
