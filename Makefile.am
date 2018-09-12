AUTOMAKE_OPTIONS = foreign

CFLAGS = -Wall -pedantic
include_HEADERS = demo.h

lib_LTLIBRARIES = libdemo.la
libdemo_la_SOURCES = libdemo.c

bin_PROGRAMS = autotools_demo
autotools_demo_SOURCES = demo.c
autotools_demo_LDADD = .libs/libdemo.la
autotools_demo_DEPENDENCIES = libdemo.la
