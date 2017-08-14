xlator_LTLIBRARIES = audit.la
xlatordir = $(libdir)/glusterfs/$(PACKAGE_VERSION)/xlator/experimental

audit_la_LDFLAGS = -module $(GF_XLATOR_DEFAULT_LDFLAGS)

audit_la_SOURCES = audit.c

audit_la_LIBADD = $(top_builddir)/libglusterfs/src/libglusterfs.la

noinst_HEADERS = 

AM_CPPFLAGS = $(GF_CPPFLAGS) -I$(top_srcdir)/libglusterfs/src

AM_CFLAGS = -Wall $(GF_CFLAGS)

CLEANFILES =
