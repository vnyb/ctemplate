# ACINIT(package_name, version, bug_report_address)
AC_INIT([myprog], [0.1], vianney.bajart@gmail.com)

# Initialize Automake
AM_INIT_AUTOMAKE

# flags
CFLAGS+="\
-Wall \
-Wextra \
-fno-common \
-Wstrict-aliasing=2 \
-Wshadow \
-Wmissing-prototypes \
-Wmissing-declarations \
-Wcast-align \
-Wuninitialized \
-Wno-strict-aliasing \
-Werror=pointer-arith \
-Werror=missing-declarations \
-Werror=redundant-decls \
-Werror=empty-body \
-Werror=format \
-Werror=format-security \
-Werror=format-nonliteral \
-Werror=init-self \
-Werror=vla \
-Wno-unused-parameter"

# Project uses libraries
AC_PROG_RANLIB

# C project
AC_LANG(C)

# Require C compiler
AC_PROG_CC

# Makefile paths
AC_CONFIG_FILES([\
    Makefile \
    libother/Makefile \
    src/Makefile \
])

# Generate configure script
AC_OUTPUT
