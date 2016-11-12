# Binaries
bin_PROGRAMS = myprog
myprog_SOURCES = main.c

# Libraries that won't be installed
noinst_LIBRARIES = libfoo.a
libfoo_a_SOURCES = \
    foo.c \
    foo.h

# Link
myprog_LDADD = \
    libfoo.a \
    ../libother/libother.a
