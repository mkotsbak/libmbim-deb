
libexec_PROGRAMS = mbim-proxy

mbim_proxy_CPPFLAGS = \
	$(MBIMPROXY_CFLAGS) \
	-I$(top_srcdir) \
	-I$(top_srcdir)/src/libmbim-glib \
	-I$(top_srcdir)/src/libmbim-glib/generated \
	-I$(top_builddir)/src/libmbim-glib \
	-I$(top_builddir)/src/libmbim-glib/generated

mbim_proxy_SOURCES = mbim-proxy.c

mbim_proxy_LDADD = \
	$(MBIMPROXY_LIBS) \
	$(top_builddir)/src/libmbim-glib/libmbim-glib.la
