lib_LIBRARIES = libnanovg.a
libnanovg_a_SOURCES=\
	nanovg.c

libnanovg_a_CFLAGS=\
	$(COVERAGE_CFLAGS)\
	-Os\
	-fstack-usage\
	-ffunction-sections -fdata-sections\
	-I$(srcdir)/../include/\
	-I$(abs_top_builddir)/include/\
	-include $(abs_top_builddir)/include/fw-config.h

libnanovg_a_LIBADD=\
	$(COVERAGE_LDADD)

libnanovg_a_CXXFLAGS=

AUTOMAKE_OPTIONS = subdir-objects
