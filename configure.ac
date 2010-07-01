dnl Process this file with autoconf to produce a configure script.
AC_INIT(sjconf-modules, 0.1.0)

dnl 2.59 is needed for AS_HELP_STRING
AC_PREREQ(2.59)

AM_INIT_AUTOMAKE([foreign])

AC_PROG_SJCONF
AC_PATH_PROG(TXT2TAGS, txt2tags)

AC_CONFIG_FILES([Makefile \
                 doc/Makefile \
                 confs/Makefile \
                 plugins/modules.py \
                 templates/Makefile \
                 templates/modules/Makefile \
                 ])

AC_OUTPUT
