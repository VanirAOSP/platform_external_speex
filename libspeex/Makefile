# Makefile.in generated by automake 1.11.1 from Makefile.am.
# libspeex/Makefile.  Generated from Makefile.in by configure.

# Copyright (C) 1994, 1995, 1996, 1997, 1998, 1999, 2000, 2001, 2002,
# 2003, 2004, 2005, 2006, 2007, 2008, 2009  Free Software Foundation,
# Inc.
# This Makefile.in is free software; the Free Software Foundation
# gives unlimited permission to copy and/or distribute it,
# with or without modifications, as long as this notice is preserved.

# This program is distributed in the hope that it will be useful,
# but WITHOUT ANY WARRANTY, to the extent permitted by law; without
# even the implied warranty of MERCHANTABILITY or FITNESS FOR A
# PARTICULAR PURPOSE.



# Disable automatic dependency tracking if using other tools than gcc and gmake
#AUTOMAKE_OPTIONS = no-dependencies




pkgdatadir = $(datadir)/speex
pkgincludedir = $(includedir)/speex
pkglibdir = $(libdir)/speex
pkglibexecdir = $(libexecdir)/speex
am__cd = CDPATH="$${ZSH_VERSION+.}$(PATH_SEPARATOR)" && cd
install_sh_DATA = $(install_sh) -c -m 644
install_sh_PROGRAM = $(install_sh) -c
install_sh_SCRIPT = $(install_sh) -c
INSTALL_HEADER = $(INSTALL_DATA)
transform = $(program_transform_name)
NORMAL_INSTALL = :
PRE_INSTALL = :
POST_INSTALL = :
NORMAL_UNINSTALL = :
PRE_UNINSTALL = :
POST_UNINSTALL = :
build_triplet = i686-pc-linux-gnu
host_triplet = arm-unknown-linux-gnu
noinst_PROGRAMS = testenc$(EXEEXT) testenc_wb$(EXEEXT) \
	testenc_uwb$(EXEEXT) testdenoise$(EXEEXT) testecho$(EXEEXT) \
	testjitter$(EXEEXT)
subdir = libspeex
DIST_COMMON = $(noinst_HEADERS) $(srcdir)/Makefile.am \
	$(srcdir)/Makefile.in
ACLOCAL_M4 = $(top_srcdir)/aclocal.m4
am__aclocal_m4_deps = $(top_srcdir)/acinclude.m4 \
	$(top_srcdir)/configure.ac
am__configure_deps = $(am__aclocal_m4_deps) $(CONFIGURE_DEPENDENCIES) \
	$(ACLOCAL_M4)
mkinstalldirs = $(install_sh) -d
CONFIG_HEADER = $(top_builddir)/config.h
CONFIG_CLEAN_FILES =
CONFIG_CLEAN_VPATH_FILES =
am__vpath_adj_setup = srcdirstrip=`echo "$(srcdir)" | sed 's|.|.|g'`;
am__vpath_adj = case $$p in \
    $(srcdir)/*) f=`echo "$$p" | sed "s|^$$srcdirstrip/||"`;; \
    *) f=$$p;; \
  esac;
am__strip_dir = f=`echo $$p | sed -e 's|^.*/||'`;
am__install_max = 40
am__nobase_strip_setup = \
  srcdirstrip=`echo "$(srcdir)" | sed 's/[].[^$$\\*|]/\\\\&/g'`
am__nobase_strip = \
  for p in $$list; do echo "$$p"; done | sed -e "s|$$srcdirstrip/||"
am__nobase_list = $(am__nobase_strip_setup); \
  for p in $$list; do echo "$$p $$p"; done | \
  sed "s| $$srcdirstrip/| |;"' / .*\//!s/ .*/ ./; s,\( .*\)/[^/]*$$,\1,' | \
  $(AWK) 'BEGIN { files["."] = "" } { files[$$2] = files[$$2] " " $$1; \
    if (++n[$$2] == $(am__install_max)) \
      { print $$2, files[$$2]; n[$$2] = 0; files[$$2] = "" } } \
    END { for (dir in files) print dir, files[dir] }'
am__base_list = \
  sed '$$!N;$$!N;$$!N;$$!N;$$!N;$$!N;$$!N;s/\n/ /g' | \
  sed '$$!N;$$!N;$$!N;$$!N;s/\n/ /g'
am__installdirs = "$(DESTDIR)$(libdir)"
LTLIBRARIES = $(lib_LTLIBRARIES)
libspeex_la_LIBADD =
am__libspeex_la_SOURCES_DIST = vorbis_psy.c cb_search.c \
	exc_10_32_table.c exc_8_128_table.c filters.c gain_table.c \
	hexc_table.c high_lsp_tables.c lsp.c ltp.c speex.c stereo.c \
	vbr.c vq.c bits.c exc_10_16_table.c exc_20_32_table.c \
	exc_5_256_table.c exc_5_64_table.c gain_table_lbr.c \
	hexc_10_32_table.c lpc.c lsp_tables_nb.c modes.c modes_wb.c \
	nb_celp.c quant_lsp.c sb_celp.c speex_callbacks.c \
	speex_header.c window.c
#am__objects_1 = vorbis_psy.lo
am_libspeex_la_OBJECTS = $(am__objects_1) cb_search.lo \
	exc_10_32_table.lo exc_8_128_table.lo filters.lo gain_table.lo \
	hexc_table.lo high_lsp_tables.lo lsp.lo ltp.lo speex.lo \
	stereo.lo vbr.lo vq.lo bits.lo exc_10_16_table.lo \
	exc_20_32_table.lo exc_5_256_table.lo exc_5_64_table.lo \
	gain_table_lbr.lo hexc_10_32_table.lo lpc.lo lsp_tables_nb.lo \
	modes.lo modes_wb.lo nb_celp.lo quant_lsp.lo sb_celp.lo \
	speex_callbacks.lo speex_header.lo window.lo
libspeex_la_OBJECTS = $(am_libspeex_la_OBJECTS)
libspeex_la_LINK = $(LIBTOOL) --tag=CC $(AM_LIBTOOLFLAGS) \
	$(LIBTOOLFLAGS) --mode=link $(CCLD) $(AM_CFLAGS) $(CFLAGS) \
	$(libspeex_la_LDFLAGS) $(LDFLAGS) -o $@
libspeexdsp_la_LIBADD =
am__libspeexdsp_la_SOURCES_DIST = preprocess.c jitter.c mdf.c \
	fftwrap.c filterbank.c resample.c buffer.c scal.c smallft.c \
	kiss_fft.c _kiss_fft_guts.h kiss_fft.h kiss_fftr.c kiss_fftr.h
##am__objects_2 = smallft.lo
am__objects_2 = kiss_fft.lo kiss_fftr.lo
am_libspeexdsp_la_OBJECTS = preprocess.lo jitter.lo mdf.lo fftwrap.lo \
	filterbank.lo resample.lo buffer.lo scal.lo $(am__objects_2)
libspeexdsp_la_OBJECTS = $(am_libspeexdsp_la_OBJECTS)
libspeexdsp_la_LINK = $(LIBTOOL) --tag=CC $(AM_LIBTOOLFLAGS) \
	$(LIBTOOLFLAGS) --mode=link $(CCLD) $(AM_CFLAGS) $(CFLAGS) \
	$(libspeexdsp_la_LDFLAGS) $(LDFLAGS) -o $@
PROGRAMS = $(noinst_PROGRAMS)
am_testdenoise_OBJECTS = testdenoise.$(OBJEXT)
testdenoise_OBJECTS = $(am_testdenoise_OBJECTS)
testdenoise_DEPENDENCIES = libspeexdsp.la
am_testecho_OBJECTS = testecho.$(OBJEXT)
testecho_OBJECTS = $(am_testecho_OBJECTS)
testecho_DEPENDENCIES = libspeexdsp.la
am_testenc_OBJECTS = testenc.$(OBJEXT)
testenc_OBJECTS = $(am_testenc_OBJECTS)
#am__DEPENDENCIES_1 = libspeexdsp.la
testenc_DEPENDENCIES = libspeex.la $(am__DEPENDENCIES_1)
am_testenc_uwb_OBJECTS = testenc_uwb.$(OBJEXT)
testenc_uwb_OBJECTS = $(am_testenc_uwb_OBJECTS)
testenc_uwb_DEPENDENCIES = libspeex.la $(am__DEPENDENCIES_1)
am_testenc_wb_OBJECTS = testenc_wb.$(OBJEXT)
testenc_wb_OBJECTS = $(am_testenc_wb_OBJECTS)
testenc_wb_DEPENDENCIES = libspeex.la $(am__DEPENDENCIES_1)
am_testjitter_OBJECTS = testjitter.$(OBJEXT)
testjitter_OBJECTS = $(am_testjitter_OBJECTS)
testjitter_DEPENDENCIES = libspeexdsp.la
DEFAULT_INCLUDES = -I. -I$(top_builddir)
depcomp = $(SHELL) $(top_srcdir)/depcomp
am__depfiles_maybe = depfiles
am__mv = mv -f
COMPILE = $(CC) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) \
	$(CPPFLAGS) $(AM_CFLAGS) $(CFLAGS)
LTCOMPILE = $(LIBTOOL) --tag=CC $(AM_LIBTOOLFLAGS) $(LIBTOOLFLAGS) \
	--mode=compile $(CC) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) \
	$(AM_CPPFLAGS) $(CPPFLAGS) $(AM_CFLAGS) $(CFLAGS)
CCLD = $(CC)
LINK = $(LIBTOOL) --tag=CC $(AM_LIBTOOLFLAGS) $(LIBTOOLFLAGS) \
	--mode=link $(CCLD) $(AM_CFLAGS) $(CFLAGS) $(AM_LDFLAGS) \
	$(LDFLAGS) -o $@
SOURCES = $(libspeex_la_SOURCES) $(libspeexdsp_la_SOURCES) \
	$(testdenoise_SOURCES) $(testecho_SOURCES) $(testenc_SOURCES) \
	$(testenc_uwb_SOURCES) $(testenc_wb_SOURCES) \
	$(testjitter_SOURCES)
DIST_SOURCES = $(am__libspeex_la_SOURCES_DIST) \
	$(am__libspeexdsp_la_SOURCES_DIST) $(testdenoise_SOURCES) \
	$(testecho_SOURCES) $(testenc_SOURCES) $(testenc_uwb_SOURCES) \
	$(testenc_wb_SOURCES) $(testjitter_SOURCES)
HEADERS = $(noinst_HEADERS)
ETAGS = etags
CTAGS = ctags
DISTFILES = $(DIST_COMMON) $(DIST_SOURCES) $(TEXINFOS) $(EXTRA_DIST)
ACLOCAL = ${SHELL} /root/speex/missing --run aclocal-1.11
AMTAR = ${SHELL} /root/speex/missing --run tar
AR = ar
AS = as
AUTOCONF = ${SHELL} /root/speex/missing --run autoconf
AUTOHEADER = ${SHELL} /root/speex/missing --run autoheader
AUTOMAKE = ${SHELL} /root/speex/missing --run automake-1.11
AWK = mawk
CC = /opt/linaro-gcc-4.5-arm-linux-gnueabi-32bit/bin/arm-linux-gnueabi-gcc
CCDEPMODE = depmode=gcc3
CFLAGS = -I../libogg-1.3.0/include/ -marm -fvisibility=hidden
CPP = /opt/linaro-gcc-4.5-arm-linux-gnueabi-32bit/bin/arm-linux-gnueabi-gcc -E
CPPFLAGS = 
CYGPATH_W = echo
DEFS = -DHAVE_CONFIG_H
DEPDIR = .deps
DLLTOOL = dlltool
DSYMUTIL = 
DUMPBIN = :
ECHO_C = 
ECHO_N = -n
ECHO_T = 
EGREP = /bin/grep -E
EXEEXT = 
FFT_CFLAGS = 
FFT_LIBS = 
FFT_PKGCONFIG = 
FGREP = /bin/grep -F
GREP = /bin/grep
INSTALL = /usr/bin/install -c
INSTALL_DATA = ${INSTALL} -m 644
INSTALL_PROGRAM = ${INSTALL}
INSTALL_SCRIPT = ${INSTALL}
INSTALL_STRIP_PROGRAM = $(install_sh) -c -s
LD = /opt/linaro-gcc-4.5-arm-linux-gnueabi-32bit/arm-linux-gnueabi/bin/ld
LDFLAGS = 
LIBOBJS = 
LIBS = -lm 
LIBTOOL = $(SHELL) $(top_builddir)/libtool
LIPO = 
LN_S = ln -s
LTLIBOBJS = 
MAINT = #
MAKEINFO = ${SHELL} /root/speex/missing --run makeinfo
MANIFEST_TOOL = :
MKDIR_P = /bin/mkdir -p
NM = nm
NMEDIT = 
OBJDUMP = objdump
OBJEXT = o
OGG_CFLAGS = -I/root/libogg-1.3.0/include
OGG_LIBS = -L/root/libogg-1.3.0/src/.libs -logg
OTOOL = 
OTOOL64 = 
PACKAGE = speex
PACKAGE_BUGREPORT = 
PACKAGE_NAME = 
PACKAGE_STRING = 
PACKAGE_TARNAME = 
PACKAGE_URL = 
PACKAGE_VERSION = 
PATH_SEPARATOR = :
PKG_CONFIG = /usr/bin/pkg-config
PKG_CONFIG_LIBDIR = 
PKG_CONFIG_PATH = 
RANLIB = ranlib
SED = /bin/sed
SET_MAKE = 
SHELL = /bin/sh
SIZE16 = short
SIZE32 = int
SPEEX_LT_AGE = 5
SPEEX_LT_CURRENT = 6
SPEEX_LT_REVISION = 0
SPEEX_VERSION = 1.2rc1
STRIP = strip
VERSION = 1.2rc1
abs_builddir = /root/speex/libspeex
abs_srcdir = /root/speex/libspeex
abs_top_builddir = /root/speex
abs_top_srcdir = /root/speex
ac_ct_AR = ar
ac_ct_CC = 
ac_ct_DUMPBIN = link -dump
am__include = include
am__leading_dot = .
am__quote = 
am__tar = ${AMTAR} chof - "$$tardir"
am__untar = ${AMTAR} xf -
bindir = ${exec_prefix}/bin
build = i686-pc-linux-gnu
build_alias = 
build_cpu = i686
build_os = linux-gnu
build_vendor = pc
builddir = .
datadir = ${datarootdir}
datarootdir = ${prefix}/share
docdir = ${datarootdir}/doc/${PACKAGE}
dvidir = ${docdir}
exec_prefix = ${prefix}
host = arm-unknown-linux-gnu
host_alias = arm-linux
host_cpu = arm
host_os = linux-gnu
host_vendor = unknown
htmldir = ${docdir}
includedir = ${prefix}/include
infodir = ${datarootdir}/info
install_sh = ${SHELL} /root/speex/install-sh
libdir = ${exec_prefix}/lib
libexecdir = ${exec_prefix}/libexec
localedir = ${datarootdir}/locale
localstatedir = ${prefix}/var
mandir = ${datarootdir}/man
mkdir_p = /bin/mkdir -p
oldincludedir = /usr/include
pdfdir = ${docdir}
prefix = /root/dump
program_transform_name = s,x,x,
psdir = ${docdir}
sbindir = ${exec_prefix}/sbin
sharedstatedir = ${prefix}/com
src = src
srcdir = .
sysconfdir = ${prefix}/etc
target_alias = 
top_build_prefix = ../
top_builddir = ..
top_srcdir = ..
VPSY_LIB = 
#VPSY_LIB = libspeexdsp.la
VPSY_SOURCE = 
#VPSY_SOURCE = vorbis_psy.c
EXTRA_DIST = echo_diagnostic.m
INCLUDES = -I$(top_builddir)/include -I$(top_builddir) -I/root/libogg-1.3.0/include 
lib_LTLIBRARIES = libspeex.la libspeexdsp.la

# Sources for compilation in the library
libspeex_la_SOURCES = $(VPSY_SOURCE) cb_search.c 	exc_10_32_table.c 	exc_8_128_table.c \
		filters.c 	gain_table.c 	hexc_table.c 	high_lsp_tables.c 	lsp.c \
		ltp.c 	speex.c 	stereo.c 	vbr.c 	vq.c bits.c exc_10_16_table.c \
	exc_20_32_table.c exc_5_256_table.c exc_5_64_table.c gain_table_lbr.c hexc_10_32_table.c \
	lpc.c lsp_tables_nb.c modes.c modes_wb.c nb_celp.c quant_lsp.c sb_celp.c \
	speex_callbacks.c speex_header.c window.c

#FFTSRC = 
##FFTSRC = smallft.c
FFTSRC = kiss_fft.c _kiss_fft_guts.h kiss_fft.h kiss_fftr.c kiss_fftr.h 
libspeexdsp_la_SOURCES = preprocess.c jitter.c mdf.c fftwrap.c filterbank.c resample.c buffer.c scal.c $(FFTSRC)
noinst_HEADERS = arch.h 	bfin.h cb_search_arm4.h 	cb_search_bfin.h 	cb_search_sse.h \
		filters.h 	filters_arm4.h 	filters_bfin.h 	filters_sse.h 	fixed_arm4.h \
		fixed_arm5e.h 	fixed_bfin.h 	fixed_debug.h 	lpc.h 	lpc_bfin.h 	ltp.h 	ltp_arm4.h \
		ltp_sse.h 	math_approx.h 		misc_bfin.h 	nb_celp.h 	quant_lsp.h 	sb_celp.h \
		stack_alloc.h 	vbr.h 	vq.h 	vq_arm4.h 	vq_bfin.h 	vq_sse.h cb_search.h fftwrap.h \
	filterbank.h fixed_generic.h lsp.h lsp_bfin.h ltp_bfin.h modes.h os_support.h \
	pseudofloat.h quant_lsp_bfin.h smallft.h vorbis_psy.h resample_sse.h

libspeex_la_LDFLAGS = -no-undefined -version-info 6:0:5
libspeexdsp_la_LDFLAGS = -no-undefined -version-info 6:0:5
testenc_SOURCES = testenc.c
testenc_LDADD = libspeex.la $(VPSY_LIB)
testenc_wb_SOURCES = testenc_wb.c
testenc_wb_LDADD = libspeex.la  $(VPSY_LIB)
testenc_uwb_SOURCES = testenc_uwb.c
testenc_uwb_LDADD = libspeex.la $(VPSY_LIB)
testdenoise_SOURCES = testdenoise.c
testdenoise_LDADD = libspeexdsp.la 
testecho_SOURCES = testecho.c
testecho_LDADD = libspeexdsp.la 
testjitter_SOURCES = testjitter.c
testjitter_LDADD = libspeexdsp.la 
all: all-am

.SUFFIXES:
.SUFFIXES: .c .lo .o .obj
$(srcdir)/Makefile.in: # $(srcdir)/Makefile.am  $(am__configure_deps)
	@for dep in $?; do \
	  case '$(am__configure_deps)' in \
	    *$$dep*) \
	      ( cd $(top_builddir) && $(MAKE) $(AM_MAKEFLAGS) am--refresh ) \
	        && { if test -f $@; then exit 0; else break; fi; }; \
	      exit 1;; \
	  esac; \
	done; \
	echo ' cd $(top_srcdir) && $(AUTOMAKE) --gnu libspeex/Makefile'; \
	$(am__cd) $(top_srcdir) && \
	  $(AUTOMAKE) --gnu libspeex/Makefile
.PRECIOUS: Makefile
Makefile: $(srcdir)/Makefile.in $(top_builddir)/config.status
	@case '$?' in \
	  *config.status*) \
	    cd $(top_builddir) && $(MAKE) $(AM_MAKEFLAGS) am--refresh;; \
	  *) \
	    echo ' cd $(top_builddir) && $(SHELL) ./config.status $(subdir)/$@ $(am__depfiles_maybe)'; \
	    cd $(top_builddir) && $(SHELL) ./config.status $(subdir)/$@ $(am__depfiles_maybe);; \
	esac;

$(top_builddir)/config.status: $(top_srcdir)/configure $(CONFIG_STATUS_DEPENDENCIES)
	cd $(top_builddir) && $(MAKE) $(AM_MAKEFLAGS) am--refresh

$(top_srcdir)/configure: # $(am__configure_deps)
	cd $(top_builddir) && $(MAKE) $(AM_MAKEFLAGS) am--refresh
$(ACLOCAL_M4): # $(am__aclocal_m4_deps)
	cd $(top_builddir) && $(MAKE) $(AM_MAKEFLAGS) am--refresh
$(am__aclocal_m4_deps):
install-libLTLIBRARIES: $(lib_LTLIBRARIES)
	@$(NORMAL_INSTALL)
	test -z "$(libdir)" || $(MKDIR_P) "$(DESTDIR)$(libdir)"
	@list='$(lib_LTLIBRARIES)'; test -n "$(libdir)" || list=; \
	list2=; for p in $$list; do \
	  if test -f $$p; then \
	    list2="$$list2 $$p"; \
	  else :; fi; \
	done; \
	test -z "$$list2" || { \
	  echo " $(LIBTOOL) $(AM_LIBTOOLFLAGS) $(LIBTOOLFLAGS) --mode=install $(INSTALL) $(INSTALL_STRIP_FLAG) $$list2 '$(DESTDIR)$(libdir)'"; \
	  $(LIBTOOL) $(AM_LIBTOOLFLAGS) $(LIBTOOLFLAGS) --mode=install $(INSTALL) $(INSTALL_STRIP_FLAG) $$list2 "$(DESTDIR)$(libdir)"; \
	}

uninstall-libLTLIBRARIES:
	@$(NORMAL_UNINSTALL)
	@list='$(lib_LTLIBRARIES)'; test -n "$(libdir)" || list=; \
	for p in $$list; do \
	  $(am__strip_dir) \
	  echo " $(LIBTOOL) $(AM_LIBTOOLFLAGS) $(LIBTOOLFLAGS) --mode=uninstall rm -f '$(DESTDIR)$(libdir)/$$f'"; \
	  $(LIBTOOL) $(AM_LIBTOOLFLAGS) $(LIBTOOLFLAGS) --mode=uninstall rm -f "$(DESTDIR)$(libdir)/$$f"; \
	done

clean-libLTLIBRARIES:
	-test -z "$(lib_LTLIBRARIES)" || rm -f $(lib_LTLIBRARIES)
	@list='$(lib_LTLIBRARIES)'; for p in $$list; do \
	  dir="`echo $$p | sed -e 's|/[^/]*$$||'`"; \
	  test "$$dir" != "$$p" || dir=.; \
	  echo "rm -f \"$${dir}/so_locations\""; \
	  rm -f "$${dir}/so_locations"; \
	done
libspeex.la: $(libspeex_la_OBJECTS) $(libspeex_la_DEPENDENCIES) 
	$(libspeex_la_LINK) -rpath $(libdir) $(libspeex_la_OBJECTS) $(libspeex_la_LIBADD) $(LIBS)
libspeexdsp.la: $(libspeexdsp_la_OBJECTS) $(libspeexdsp_la_DEPENDENCIES) 
	$(libspeexdsp_la_LINK) -rpath $(libdir) $(libspeexdsp_la_OBJECTS) $(libspeexdsp_la_LIBADD) $(LIBS)

clean-noinstPROGRAMS:
	@list='$(noinst_PROGRAMS)'; test -n "$$list" || exit 0; \
	echo " rm -f" $$list; \
	rm -f $$list || exit $$?; \
	test -n "$(EXEEXT)" || exit 0; \
	list=`for p in $$list; do echo "$$p"; done | sed 's/$(EXEEXT)$$//'`; \
	echo " rm -f" $$list; \
	rm -f $$list
testdenoise$(EXEEXT): $(testdenoise_OBJECTS) $(testdenoise_DEPENDENCIES) 
	@rm -f testdenoise$(EXEEXT)
	$(LINK) $(testdenoise_OBJECTS) $(testdenoise_LDADD) $(LIBS)
testecho$(EXEEXT): $(testecho_OBJECTS) $(testecho_DEPENDENCIES) 
	@rm -f testecho$(EXEEXT)
	$(LINK) $(testecho_OBJECTS) $(testecho_LDADD) $(LIBS)
testenc$(EXEEXT): $(testenc_OBJECTS) $(testenc_DEPENDENCIES) 
	@rm -f testenc$(EXEEXT)
	$(LINK) $(testenc_OBJECTS) $(testenc_LDADD) $(LIBS)
testenc_uwb$(EXEEXT): $(testenc_uwb_OBJECTS) $(testenc_uwb_DEPENDENCIES) 
	@rm -f testenc_uwb$(EXEEXT)
	$(LINK) $(testenc_uwb_OBJECTS) $(testenc_uwb_LDADD) $(LIBS)
testenc_wb$(EXEEXT): $(testenc_wb_OBJECTS) $(testenc_wb_DEPENDENCIES) 
	@rm -f testenc_wb$(EXEEXT)
	$(LINK) $(testenc_wb_OBJECTS) $(testenc_wb_LDADD) $(LIBS)
testjitter$(EXEEXT): $(testjitter_OBJECTS) $(testjitter_DEPENDENCIES) 
	@rm -f testjitter$(EXEEXT)
	$(LINK) $(testjitter_OBJECTS) $(testjitter_LDADD) $(LIBS)

mostlyclean-compile:
	-rm -f *.$(OBJEXT)

distclean-compile:
	-rm -f *.tab.c

include ./$(DEPDIR)/bits.Plo
include ./$(DEPDIR)/buffer.Plo
include ./$(DEPDIR)/cb_search.Plo
include ./$(DEPDIR)/exc_10_16_table.Plo
include ./$(DEPDIR)/exc_10_32_table.Plo
include ./$(DEPDIR)/exc_20_32_table.Plo
include ./$(DEPDIR)/exc_5_256_table.Plo
include ./$(DEPDIR)/exc_5_64_table.Plo
include ./$(DEPDIR)/exc_8_128_table.Plo
include ./$(DEPDIR)/fftwrap.Plo
include ./$(DEPDIR)/filterbank.Plo
include ./$(DEPDIR)/filters.Plo
include ./$(DEPDIR)/gain_table.Plo
include ./$(DEPDIR)/gain_table_lbr.Plo
include ./$(DEPDIR)/hexc_10_32_table.Plo
include ./$(DEPDIR)/hexc_table.Plo
include ./$(DEPDIR)/high_lsp_tables.Plo
include ./$(DEPDIR)/jitter.Plo
include ./$(DEPDIR)/kiss_fft.Plo
include ./$(DEPDIR)/kiss_fftr.Plo
include ./$(DEPDIR)/lpc.Plo
include ./$(DEPDIR)/lsp.Plo
include ./$(DEPDIR)/lsp_tables_nb.Plo
include ./$(DEPDIR)/ltp.Plo
include ./$(DEPDIR)/mdf.Plo
include ./$(DEPDIR)/modes.Plo
include ./$(DEPDIR)/modes_wb.Plo
include ./$(DEPDIR)/nb_celp.Plo
include ./$(DEPDIR)/preprocess.Plo
include ./$(DEPDIR)/quant_lsp.Plo
include ./$(DEPDIR)/resample.Plo
include ./$(DEPDIR)/sb_celp.Plo
include ./$(DEPDIR)/scal.Plo
include ./$(DEPDIR)/smallft.Plo
include ./$(DEPDIR)/speex.Plo
include ./$(DEPDIR)/speex_callbacks.Plo
include ./$(DEPDIR)/speex_header.Plo
include ./$(DEPDIR)/stereo.Plo
include ./$(DEPDIR)/testdenoise.Po
include ./$(DEPDIR)/testecho.Po
include ./$(DEPDIR)/testenc.Po
include ./$(DEPDIR)/testenc_uwb.Po
include ./$(DEPDIR)/testenc_wb.Po
include ./$(DEPDIR)/testjitter.Po
include ./$(DEPDIR)/vbr.Plo
include ./$(DEPDIR)/vorbis_psy.Plo
include ./$(DEPDIR)/vq.Plo
include ./$(DEPDIR)/window.Plo

.c.o:
	$(COMPILE) -MT $@ -MD -MP -MF $(DEPDIR)/$*.Tpo -c -o $@ $<
	$(am__mv) $(DEPDIR)/$*.Tpo $(DEPDIR)/$*.Po
#	source='$<' object='$@' libtool=no \
#	DEPDIR=$(DEPDIR) $(CCDEPMODE) $(depcomp) \
#	$(COMPILE) -c $<

.c.obj:
	$(COMPILE) -MT $@ -MD -MP -MF $(DEPDIR)/$*.Tpo -c -o $@ `$(CYGPATH_W) '$<'`
	$(am__mv) $(DEPDIR)/$*.Tpo $(DEPDIR)/$*.Po
#	source='$<' object='$@' libtool=no \
#	DEPDIR=$(DEPDIR) $(CCDEPMODE) $(depcomp) \
#	$(COMPILE) -c `$(CYGPATH_W) '$<'`

.c.lo:
	$(LTCOMPILE) -MT $@ -MD -MP -MF $(DEPDIR)/$*.Tpo -c -o $@ $<
	$(am__mv) $(DEPDIR)/$*.Tpo $(DEPDIR)/$*.Plo
#	source='$<' object='$@' libtool=yes \
#	DEPDIR=$(DEPDIR) $(CCDEPMODE) $(depcomp) \
#	$(LTCOMPILE) -c -o $@ $<

mostlyclean-libtool:
	-rm -f *.lo

clean-libtool:
	-rm -rf .libs _libs

ID: $(HEADERS) $(SOURCES) $(LISP) $(TAGS_FILES)
	list='$(SOURCES) $(HEADERS) $(LISP) $(TAGS_FILES)'; \
	unique=`for i in $$list; do \
	    if test -f "$$i"; then echo $$i; else echo $(srcdir)/$$i; fi; \
	  done | \
	  $(AWK) '{ files[$$0] = 1; nonempty = 1; } \
	      END { if (nonempty) { for (i in files) print i; }; }'`; \
	mkid -fID $$unique
tags: TAGS

TAGS:  $(HEADERS) $(SOURCES)  $(TAGS_DEPENDENCIES) \
		$(TAGS_FILES) $(LISP)
	set x; \
	here=`pwd`; \
	list='$(SOURCES) $(HEADERS)  $(LISP) $(TAGS_FILES)'; \
	unique=`for i in $$list; do \
	    if test -f "$$i"; then echo $$i; else echo $(srcdir)/$$i; fi; \
	  done | \
	  $(AWK) '{ files[$$0] = 1; nonempty = 1; } \
	      END { if (nonempty) { for (i in files) print i; }; }'`; \
	shift; \
	if test -z "$(ETAGS_ARGS)$$*$$unique"; then :; else \
	  test -n "$$unique" || unique=$$empty_fix; \
	  if test $$# -gt 0; then \
	    $(ETAGS) $(ETAGSFLAGS) $(AM_ETAGSFLAGS) $(ETAGS_ARGS) \
	      "$$@" $$unique; \
	  else \
	    $(ETAGS) $(ETAGSFLAGS) $(AM_ETAGSFLAGS) $(ETAGS_ARGS) \
	      $$unique; \
	  fi; \
	fi
ctags: CTAGS
CTAGS:  $(HEADERS) $(SOURCES)  $(TAGS_DEPENDENCIES) \
		$(TAGS_FILES) $(LISP)
	list='$(SOURCES) $(HEADERS)  $(LISP) $(TAGS_FILES)'; \
	unique=`for i in $$list; do \
	    if test -f "$$i"; then echo $$i; else echo $(srcdir)/$$i; fi; \
	  done | \
	  $(AWK) '{ files[$$0] = 1; nonempty = 1; } \
	      END { if (nonempty) { for (i in files) print i; }; }'`; \
	test -z "$(CTAGS_ARGS)$$unique" \
	  || $(CTAGS) $(CTAGSFLAGS) $(AM_CTAGSFLAGS) $(CTAGS_ARGS) \
	     $$unique

GTAGS:
	here=`$(am__cd) $(top_builddir) && pwd` \
	  && $(am__cd) $(top_srcdir) \
	  && gtags -i $(GTAGS_ARGS) "$$here"

distclean-tags:
	-rm -f TAGS ID GTAGS GRTAGS GSYMS GPATH tags

distdir: $(DISTFILES)
	@srcdirstrip=`echo "$(srcdir)" | sed 's/[].[^$$\\*]/\\\\&/g'`; \
	topsrcdirstrip=`echo "$(top_srcdir)" | sed 's/[].[^$$\\*]/\\\\&/g'`; \
	list='$(DISTFILES)'; \
	  dist_files=`for file in $$list; do echo $$file; done | \
	  sed -e "s|^$$srcdirstrip/||;t" \
	      -e "s|^$$topsrcdirstrip/|$(top_builddir)/|;t"`; \
	case $$dist_files in \
	  */*) $(MKDIR_P) `echo "$$dist_files" | \
			   sed '/\//!d;s|^|$(distdir)/|;s,/[^/]*$$,,' | \
			   sort -u` ;; \
	esac; \
	for file in $$dist_files; do \
	  if test -f $$file || test -d $$file; then d=.; else d=$(srcdir); fi; \
	  if test -d $$d/$$file; then \
	    dir=`echo "/$$file" | sed -e 's,/[^/]*$$,,'`; \
	    if test -d "$(distdir)/$$file"; then \
	      find "$(distdir)/$$file" -type d ! -perm -700 -exec chmod u+rwx {} \;; \
	    fi; \
	    if test -d $(srcdir)/$$file && test $$d != $(srcdir); then \
	      cp -fpR $(srcdir)/$$file "$(distdir)$$dir" || exit 1; \
	      find "$(distdir)/$$file" -type d ! -perm -700 -exec chmod u+rwx {} \;; \
	    fi; \
	    cp -fpR $$d/$$file "$(distdir)$$dir" || exit 1; \
	  else \
	    test -f "$(distdir)/$$file" \
	    || cp -p $$d/$$file "$(distdir)/$$file" \
	    || exit 1; \
	  fi; \
	done
check-am: all-am
check: check-am
all-am: Makefile $(LTLIBRARIES) $(PROGRAMS) $(HEADERS)
installdirs:
	for dir in "$(DESTDIR)$(libdir)"; do \
	  test -z "$$dir" || $(MKDIR_P) "$$dir"; \
	done
install: install-am
install-exec: install-exec-am
install-data: install-data-am
uninstall: uninstall-am

install-am: all-am
	@$(MAKE) $(AM_MAKEFLAGS) install-exec-am install-data-am

installcheck: installcheck-am
install-strip:
	$(MAKE) $(AM_MAKEFLAGS) INSTALL_PROGRAM="$(INSTALL_STRIP_PROGRAM)" \
	  install_sh_PROGRAM="$(INSTALL_STRIP_PROGRAM)" INSTALL_STRIP_FLAG=-s \
	  `test -z '$(STRIP)' || \
	    echo "INSTALL_PROGRAM_ENV=STRIPPROG='$(STRIP)'"` install
mostlyclean-generic:

clean-generic:

distclean-generic:
	-test -z "$(CONFIG_CLEAN_FILES)" || rm -f $(CONFIG_CLEAN_FILES)
	-test . = "$(srcdir)" || test -z "$(CONFIG_CLEAN_VPATH_FILES)" || rm -f $(CONFIG_CLEAN_VPATH_FILES)

maintainer-clean-generic:
	@echo "This command is intended for maintainers to use"
	@echo "it deletes files that may require special tools to rebuild."
clean: clean-am

clean-am: clean-generic clean-libLTLIBRARIES clean-libtool \
	clean-noinstPROGRAMS mostlyclean-am

distclean: distclean-am
	-rm -rf ./$(DEPDIR)
	-rm -f Makefile
distclean-am: clean-am distclean-compile distclean-generic \
	distclean-tags

dvi: dvi-am

dvi-am:

html: html-am

html-am:

info: info-am

info-am:

install-data-am:

install-dvi: install-dvi-am

install-dvi-am:

install-exec-am: install-libLTLIBRARIES

install-html: install-html-am

install-html-am:

install-info: install-info-am

install-info-am:

install-man:

install-pdf: install-pdf-am

install-pdf-am:

install-ps: install-ps-am

install-ps-am:

installcheck-am:

maintainer-clean: maintainer-clean-am
	-rm -rf ./$(DEPDIR)
	-rm -f Makefile
maintainer-clean-am: distclean-am maintainer-clean-generic

mostlyclean: mostlyclean-am

mostlyclean-am: mostlyclean-compile mostlyclean-generic \
	mostlyclean-libtool

pdf: pdf-am

pdf-am:

ps: ps-am

ps-am:

uninstall-am: uninstall-libLTLIBRARIES

.MAKE: install-am install-strip

.PHONY: CTAGS GTAGS all all-am check check-am clean clean-generic \
	clean-libLTLIBRARIES clean-libtool clean-noinstPROGRAMS ctags \
	distclean distclean-compile distclean-generic \
	distclean-libtool distclean-tags distdir dvi dvi-am html \
	html-am info info-am install install-am install-data \
	install-data-am install-dvi install-dvi-am install-exec \
	install-exec-am install-html install-html-am install-info \
	install-info-am install-libLTLIBRARIES install-man install-pdf \
	install-pdf-am install-ps install-ps-am install-strip \
	installcheck installcheck-am installdirs maintainer-clean \
	maintainer-clean-generic mostlyclean mostlyclean-compile \
	mostlyclean-generic mostlyclean-libtool pdf pdf-am ps ps-am \
	tags uninstall uninstall-am uninstall-libLTLIBRARIES


# Tell versions [3.59,3.63) of GNU make to not export all variables.
# Otherwise a system limit (for SysV at least) may be exceeded.
.NOEXPORT:
