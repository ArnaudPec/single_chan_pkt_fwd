ACLOCAL_AMFLAGS= -I m4

AM_CXXFLAGS = \
-I. \
-DPACKAGE_BIN_DIR=\"$(bindir)\" \
-DPACKAGE_LIB_DIR=\"$(libdir)\" \
@CFLAGS@

bin_PROGRAMS = sgw

sgw_CFLAGS = -x c++

sgw_SOURCES = \
base64.c \
main.cpp

sgw_LDFLAGS = \
-lpthread \
-lwiringPi
