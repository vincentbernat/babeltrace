AM_CFLAGS = $(PACKAGE_CFLAGS) -I$(top_srcdir)/include

lib_LTLIBRARIES = libbabeltrace-ctf-metadata.la

libbabeltrace_ctf_metadata_la_SOURCES = \
	ctf-metadata.c

libbabeltrace_ctf_metadata_la_LDFLAGS = \
	-Wl,--no-as-needed

libbabeltrace_ctf_metadata_la_LIBADD = \
	$(top_builddir)/lib/libbabeltrace.la
