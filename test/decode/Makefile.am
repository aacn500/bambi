AM_CPPFLAGS = $(HTSLIB_CPPFLAGS)
AM_LDFLAGS = $(HTSLIB_LDFLAGS)

bin_PROGRAMS = t_decode
t_decode_SOURCES = t_decode.c
t_decode_CFLAGS = -I$(top_srcdir)/src -DDATA_DIR=$(abs_srcdir)
t_decode_LDADD = $(HTSLIB_HOME)/lib/libhts.a -ldl -lxml2 -lz -llzma -lbz2 -lpthread
