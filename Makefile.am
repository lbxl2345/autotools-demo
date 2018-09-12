AUTOMAKE_OPTIONS = foreign

CFLAGS = -Wall -pedantic
include_HEADERS = demo.h

lib_LTLIBRARIES = libautotools_demo.la
libautotools_demo_la_SOURCES = libdemo.c

bin_PROGRAMS = autotools_demo
autotools_demo_SOURCES = demo.c
autotools_demo_LDADD = .libs/libautotools_demo.la
autotools_demo_DEPENDENCIES = libautotools_demo.la
