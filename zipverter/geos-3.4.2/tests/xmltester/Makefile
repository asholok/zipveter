# Makefile.in generated by automake 1.11.1 from Makefile.am.
# tests/xmltester/Makefile.  Generated from Makefile.in by configure.

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



#
# This file is part of project GEOS (http://trac.osgeo.org/geos/) 
#
#prefix=/usr/local
#top_srcdir=../..
#top_builddir=../..


pkgdatadir = $(datadir)/geos
pkgincludedir = $(includedir)/geos
pkglibdir = $(libdir)/geos
pkglibexecdir = $(libexecdir)/geos
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
build_triplet = x86_64-unknown-linux-gnu
host_triplet = x86_64-unknown-linux-gnu
target_triplet = x86_64-unknown-linux-gnu
noinst_PROGRAMS = SimpleWKTTester$(EXEEXT) XMLTester$(EXEEXT)
subdir = tests/xmltester
DIST_COMMON = $(srcdir)/Makefile.am $(srcdir)/Makefile.in
ACLOCAL_M4 = $(top_srcdir)/aclocal.m4
am__aclocal_m4_deps = $(top_srcdir)/macros/ac_pkg_swig.m4 \
	$(top_srcdir)/macros/ac_python_devel.m4 \
	$(top_srcdir)/macros/libtool.m4 \
	$(top_srcdir)/macros/ltoptions.m4 \
	$(top_srcdir)/macros/ltsugar.m4 \
	$(top_srcdir)/macros/ltversion.m4 \
	$(top_srcdir)/macros/lt~obsolete.m4 \
	$(top_srcdir)/macros/python.m4 $(top_srcdir)/macros/ruby.m4 \
	$(top_srcdir)/configure.in
am__configure_deps = $(am__aclocal_m4_deps) $(CONFIGURE_DEPENDENCIES) \
	$(ACLOCAL_M4)
mkinstalldirs = $(install_sh) -d
CONFIG_HEADER = $(top_builddir)/include/config.h \
	$(top_builddir)/include/geos/platform.h
CONFIG_CLEAN_FILES =
CONFIG_CLEAN_VPATH_FILES =
PROGRAMS = $(noinst_PROGRAMS)
am_SimpleWKTTester_OBJECTS = SimpleWKTTester.$(OBJEXT)
SimpleWKTTester_OBJECTS = $(am_SimpleWKTTester_OBJECTS)
SimpleWKTTester_DEPENDENCIES = $(LIBS)
am_XMLTester_OBJECTS = XMLTester-XMLTester.$(OBJEXT) \
	XMLTester-tinyxml.$(OBJEXT) XMLTester-tinystr.$(OBJEXT) \
	XMLTester-tinyxmlerror.$(OBJEXT) \
	XMLTester-tinyxmlparser.$(OBJEXT) \
	XMLTester-BufferResultMatcher.$(OBJEXT) \
	XMLTester-SingleSidedBufferResultMatcher.$(OBJEXT)
XMLTester_OBJECTS = $(am_XMLTester_OBJECTS)
XMLTester_DEPENDENCIES = $(LIBS)
XMLTester_LINK = $(LIBTOOL) --tag=CXX $(AM_LIBTOOLFLAGS) \
	$(LIBTOOLFLAGS) --mode=link $(CXXLD) $(XMLTester_CXXFLAGS) \
	$(CXXFLAGS) $(AM_LDFLAGS) $(LDFLAGS) -o $@
DEFAULT_INCLUDES = -I. -I$(top_builddir)/include -I$(top_builddir)/include/geos
depcomp = $(SHELL) $(top_srcdir)/depcomp
am__depfiles_maybe = depfiles
am__mv = mv -f
CXXCOMPILE = $(CXX) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) \
	$(AM_CPPFLAGS) $(CPPFLAGS) $(AM_CXXFLAGS) $(CXXFLAGS)
LTCXXCOMPILE = $(LIBTOOL) --tag=CXX $(AM_LIBTOOLFLAGS) $(LIBTOOLFLAGS) \
	--mode=compile $(CXX) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) \
	$(AM_CPPFLAGS) $(CPPFLAGS) $(AM_CXXFLAGS) $(CXXFLAGS)
CXXLD = $(CXX)
CXXLINK = $(LIBTOOL) --tag=CXX $(AM_LIBTOOLFLAGS) $(LIBTOOLFLAGS) \
	--mode=link $(CXXLD) $(AM_CXXFLAGS) $(CXXFLAGS) $(AM_LDFLAGS) \
	$(LDFLAGS) -o $@
COMPILE = $(CC) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) \
	$(CPPFLAGS) $(AM_CFLAGS) $(CFLAGS)
LTCOMPILE = $(LIBTOOL) --tag=CC $(AM_LIBTOOLFLAGS) $(LIBTOOLFLAGS) \
	--mode=compile $(CC) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) \
	$(AM_CPPFLAGS) $(CPPFLAGS) $(AM_CFLAGS) $(CFLAGS)
CCLD = $(CC)
LINK = $(LIBTOOL) --tag=CC $(AM_LIBTOOLFLAGS) $(LIBTOOLFLAGS) \
	--mode=link $(CCLD) $(AM_CFLAGS) $(CFLAGS) $(AM_LDFLAGS) \
	$(LDFLAGS) -o $@
SOURCES = $(SimpleWKTTester_SOURCES) $(XMLTester_SOURCES)
DIST_SOURCES = $(SimpleWKTTester_SOURCES) $(XMLTester_SOURCES)
ETAGS = etags
CTAGS = ctags
am__tty_colors = \
red=; grn=; lgn=; blu=; std=
DISTFILES = $(DIST_COMMON) $(DIST_SOURCES) $(TEXINFOS) $(EXTRA_DIST)
ACLOCAL = ${SHELL} /home/asholok/envs/zipvert/geos-3.4.2/missing --run aclocal-1.11
ALLOCA = 
AMTAR = ${SHELL} /home/asholok/envs/zipvert/geos-3.4.2/missing --run tar
AM_CFLAGS =   -pedantic -Wall -ansi -Wno-long-long  -ffloat-store
AM_CXXFLAGS =  -DGEOS_INLINE  -pedantic -Wall -ansi -Wno-long-long  -ffloat-store
AR = ar
AS = as
AUTOCONF = ${SHELL} /home/asholok/envs/zipvert/geos-3.4.2/missing --run autoconf
AUTOHEADER = ${SHELL} /home/asholok/envs/zipvert/geos-3.4.2/missing --run autoheader
AUTOMAKE = ${SHELL} /home/asholok/envs/zipvert/geos-3.4.2/missing --run automake-1.11
AWK = mawk
CAPI_INTERFACE_AGE = 8
CAPI_INTERFACE_CURRENT = 9
CAPI_INTERFACE_REVISION = 2
CAPI_VERSION = 1.8.2
CAPI_VERSION_MAJOR = 1
CAPI_VERSION_MINOR = 8
CAPI_VERSION_PATCH = 2
CC = gcc
CCDEPMODE = depmode=gcc3
CFLAGS = -g -O2
CPP = gcc -E
CPPFLAGS = 
CXX = g++
CXXCPP = g++ -E
CXXDEPMODE = depmode=gcc3
CXXFLAGS = -g -O2
CYGPATH_W = echo
DEFS = -DHAVE_CONFIG_H
DEPDIR = .deps
DLLTOOL = dlltool
DSYMUTIL = 
DUMPBIN = 
ECHO_C = 
ECHO_N = -n
ECHO_T = 
EGREP = /bin/grep -E
EXEEXT = 
FGREP = /bin/grep -F
GREP = /bin/grep
INLINE_FLAGS = -DGEOS_INLINE
INSTALL = /usr/bin/install -c
INSTALL_DATA = ${INSTALL} -m 644
INSTALL_PROGRAM = ${INSTALL}
INSTALL_SCRIPT = ${INSTALL}
INSTALL_STRIP_PROGRAM = $(install_sh) -c -s
INTERFACE_AGE = 
INTERFACE_CURRENT = 
INTERFACE_REVISION = 
JTS_PORT = 1.12.0
LD = /usr/bin/ld -m elf_x86_64
LDFLAGS = 
LIBOBJS = 
#bin_PROGRAMS = XMLTester
# CTS
LIBS = $(top_builddir)/src/libgeos.la
LIBTOOL = $(SHELL) $(top_builddir)/libtool
LIPO = 
LN_S = ln -s
LTLIBOBJS = 
MAINT = #
MAKEINFO = ${SHELL} /home/asholok/envs/zipvert/geos-3.4.2/missing --run makeinfo
MKDIR_P = /bin/mkdir -p
NM = /usr/bin/nm -B
NMEDIT = 
OBJDUMP = objdump
OBJEXT = o
OTOOL = 
OTOOL64 = 
PACKAGE = geos
PACKAGE_BUGREPORT = 
PACKAGE_NAME = 
PACKAGE_STRING = 
PACKAGE_TARNAME = 
PACKAGE_URL = 
PACKAGE_VERSION = 
PATH_SEPARATOR = :
PHP = 
PHPUNIT = 
PHP_CONFIG = 
PYTHON = 
PYTHON_CPPFLAGS = 
PYTHON_EXEC_PREFIX = 
PYTHON_EXTRA_LIBS = 
PYTHON_LDFLAGS = 
PYTHON_PLATFORM = 
PYTHON_PREFIX = 
PYTHON_SITE_PKG = 
PYTHON_VERSION = 
RANLIB = ranlib
RUBY = 
RUBY_BIN_DIR = 
RUBY_EXTENSION_DIR = 
RUBY_INCLUDE_DIR = 
RUBY_LIB_DIR = 
RUBY_SHARED_LIB = 
RUBY_SITE_ARCH = 
RUBY_SO_NAME = 
RUBY_VERSION = 
SED = /bin/sed
SET_MAKE = 
SHELL = /bin/bash
STRIP = strip
SWIG = 
SWIG_LIB = 
SWIG_PYTHON_CPPFLAGS = 
SWIG_PYTHON_OPT = 
VERSION = 3.4.2
VERSION_MAJOR = 3
VERSION_MINOR = 4
VERSION_PATCH = 2
abs_builddir = /home/asholok/envs/zipvert/geos-3.4.2/tests/xmltester
abs_srcdir = /home/asholok/envs/zipvert/geos-3.4.2/tests/xmltester
abs_top_builddir = /home/asholok/envs/zipvert/geos-3.4.2
abs_top_srcdir = /home/asholok/envs/zipvert/geos-3.4.2
ac_ct_CC = gcc
ac_ct_CXX = g++
ac_ct_DUMPBIN = 
am__include = include
am__leading_dot = .
am__quote = 
am__tar = ${AMTAR} chof - "$$tardir"
am__untar = ${AMTAR} xf -
bindir = ${exec_prefix}/bin
build = x86_64-unknown-linux-gnu
build_alias = 
build_cpu = x86_64
build_os = linux-gnu
build_vendor = unknown
builddir = .
datadir = ${datarootdir}
datarootdir = ${prefix}/share
docdir = ${datarootdir}/doc/${PACKAGE}
dvidir = ${docdir}
exec_prefix = ${prefix}
host = x86_64-unknown-linux-gnu
host_alias = 
host_cpu = x86_64
host_os = linux-gnu
host_vendor = unknown
htmldir = ${docdir}
includedir = ${prefix}/include
infodir = ${datarootdir}/info
install_sh = ${SHELL} /home/asholok/envs/zipvert/geos-3.4.2/install-sh
libdir = ${exec_prefix}/lib
libexecdir = ${exec_prefix}/libexec
localedir = ${datarootdir}/locale
localstatedir = ${prefix}/var
lt_ECHO = echo
mandir = ${datarootdir}/man
mkdir_p = /bin/mkdir -p
oldincludedir = /usr/include
pdfdir = ${docdir}
pkgpyexecdir = 
pkgpythondir = 
prefix = /usr/local
program_transform_name = s,x,x,
psdir = ${docdir}
pyexecdir = 
pythondir = 
sbindir = ${exec_prefix}/sbin
sharedstatedir = ${prefix}/com
srcdir = .
sysconfdir = ${prefix}/etc
target = x86_64-unknown-linux-gnu
target_alias = 
target_cpu = x86_64
target_os = linux-gnu
target_vendor = unknown
top_build_prefix = ../../
top_builddir = ../..
top_srcdir = ../..
TESTS = testrunner
CLEANFILES = testrunner 
EXTRA_DIST = testrunner.sh CMakeLists.txt $(XMLTESTS)
SAFE_XMLTESTS = $(srcdir)/tests/testLeaksBig.xml \
	$(srcdir)/tests/split.xml \
	$(srcdir)/tests/hexwkb.xml \
	$(srcdir)/tests/test.xml \
	$(srcdir)/tests/linemerge.xml \
	$(srcdir)/tests/TestIsValid.xml \
	$(srcdir)/tests/robustness.xml \
	$(srcdir)/tests/buffer.xml \
	$(srcdir)/tests/singlesidedbuffer.xml \
	$(srcdir)/tests/ticket/bug176.xml \
	$(srcdir)/tests/ticket/bug188.xml \
	$(srcdir)/tests/ticket/bug244.xml \
	$(srcdir)/tests/ticket/bug275.xml \
	$(srcdir)/tests/ticket/bug350.xml \
	$(srcdir)/tests/ticket/bug356.xml \
	$(srcdir)/tests/ticket/bug358.xml \
	$(srcdir)/tests/ticket/bug360.xml \
	$(srcdir)/tests/ticket/bug366.xml \
	$(srcdir)/tests/ticket/bug392.xml \
	$(srcdir)/tests/ticket/bug398.xml \
	$(srcdir)/tests/ticket/bug434.xml \
	$(srcdir)/tests/ticket/bug459.xml \
	$(srcdir)/tests/ticket/bug527.xml \
	$(srcdir)/tests/ticket/bug582.xml \
	$(srcdir)/tests/ticket/bug586.xml \
	$(srcdir)/tests/ticket/bug599.xml \
	$(srcdir)/tests/ticket/bug605.xml \
	$(srcdir)/tests/ticket/bug615.xml \
	$(srcdir)/tests/general/TestBoundary.xml \
	$(srcdir)/tests/general/TestBuffer.xml \
	$(srcdir)/tests/general/TestBufferMitredJoin.xml \
	$(srcdir)/tests/general/TestCentroid.xml \
	$(srcdir)/tests/general/TestConvexHull.xml \
	$(srcdir)/tests/general/TestConvexHull-big.xml \
	$(srcdir)/tests/general/TestDistance.xml \
	$(srcdir)/tests/general/TestFunctionAAPrec.xml \
	$(srcdir)/tests/general/TestFunctionAA.xml \
	$(srcdir)/tests/general/TestFunctionLAPrec.xml \
	$(srcdir)/tests/general/TestFunctionLA.xml \
	$(srcdir)/tests/general/TestFunctionLLPrec.xml \
	$(srcdir)/tests/general/TestFunctionLL.xml \
	$(srcdir)/tests/general/TestFunctionPA.xml \
	$(srcdir)/tests/general/TestFunctionPLPrec.xml \
	$(srcdir)/tests/general/TestFunctionPL.xml \
	$(srcdir)/tests/general/TestFunctionPP.xml \
	$(srcdir)/tests/general/TestInteriorPoint.xml \
	$(srcdir)/tests/general/TestRectanglePredicate.xml \
	$(srcdir)/tests/general/TestRelateAA.xml \
	$(srcdir)/tests/general/TestRelateLA.xml \
	$(srcdir)/tests/general/TestRelateLL.xml \
	$(srcdir)/tests/general/TestRelatePL.xml \
	$(srcdir)/tests/general/TestRelateAC.xml \
	$(srcdir)/tests/general/TestRelateLC.xml \
	$(srcdir)/tests/general/TestRelatePA.xml \
	$(srcdir)/tests/general/TestRelatePP.xml \
	$(srcdir)/tests/general/TestSimple.xml \
	$(srcdir)/tests/general/TestUnaryUnion.xml \
	$(srcdir)/tests/general/TestUnaryUnionFloating.xml \
	$(srcdir)/tests/general/TestValid.xml \
	$(srcdir)/tests/general/TestValid2.xml \
	$(srcdir)/tests/general/TestValid2-big.xml \
	$(srcdir)/tests/general/TestWithinDistance.xml \
	$(srcdir)/tests/stmlf/stmlf-cases-20061020.xml \
	$(srcdir)/tests/stmlf/stmlf-cases-20061020-invalid-output.xml \
	$(srcdir)/tests/stmlf/stmlf-cases-20070119.xml \
	$(srcdir)/tests/robust/TestRobustOverlayFixed.xml \
	$(srcdir)/tests/robust/TestRobustRelate.xml \
	$(srcdir)/tests/fme.xml \
	$(srcdir)/tests/TestBufferExternal.xml \
	$(srcdir)/tests/TestBufferExternal2.xml \
	$(srcdir)/tests/heisenbugs.xml \
	$(srcdir)/tests/badguy3.xml \
	$(srcdir)/tests/hole_from_shell.xml \
	$(srcdir)/tests/hole_red.xml \
	$(srcdir)/tests/safe/16595.xml \
	$(srcdir)/tests/safe/16596.xml \
	$(srcdir)/tests/safe/TestBufferJagged.xml

INVALID_OUTPUT_XMLTESTS = 
FAILING_XMLTESTS = \
	$(srcdir)/tests/failure/TestOverlay.xml \
	$(srcdir)/tests/ticket/bug488.xml 

XMLTESTS = $(SAFE_XMLTESTS) $(INVALID_OUTPUT_XMLTESTS) $(FAILING_XMLTESTS)
# -lmpatrol -lbfd -lintl -liberty -limagehlp

# CTS_SOURCES = CTS.cpp
# CTS_LDADD = $(LIBS)
SimpleWKTTester_SOURCES = SimpleWKTTester.cpp
SimpleWKTTester_LDADD = $(LIBS)
XMLTester_SOURCES = \
	XMLTester.cpp \
	XMLTester.h \
	tinyxml/tinyxml.h \
	tinyxml/tinyxml.cpp \
	tinyxml/tinystr.h \
	tinyxml/tinystr.cpp \
	tinyxml/tinyxmlerror.cpp \
	tinyxml/tinyxmlparser.cpp \
	BufferResultMatcher.h \
	BufferResultMatcher.cpp \
	SingleSidedBufferResultMatcher.h \
	SingleSidedBufferResultMatcher.cpp

XMLTester_LDADD = $(LIBS)

# Intentionally drop -ansi -pedantic
# See http://trac.osgeo.org/geos/ticket/319
XMLTester_CXXFLAGS = $(INLINE_FLAGS)
INCLUDES = -I$(top_srcdir)/include -I$(top_srcdir)/src/io/tinyxml \
	-DTIXML_USE_STL
all: all-am

.SUFFIXES:
.SUFFIXES: .cpp .lo .o .obj
$(srcdir)/Makefile.in: # $(srcdir)/Makefile.am  $(am__configure_deps)
	@for dep in $?; do \
	  case '$(am__configure_deps)' in \
	    *$$dep*) \
	      ( cd $(top_builddir) && $(MAKE) $(AM_MAKEFLAGS) am--refresh ) \
	        && { if test -f $@; then exit 0; else break; fi; }; \
	      exit 1;; \
	  esac; \
	done; \
	echo ' cd $(top_srcdir) && $(AUTOMAKE) --gnu tests/xmltester/Makefile'; \
	$(am__cd) $(top_srcdir) && \
	  $(AUTOMAKE) --gnu tests/xmltester/Makefile
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

clean-noinstPROGRAMS:
	@list='$(noinst_PROGRAMS)'; test -n "$$list" || exit 0; \
	echo " rm -f" $$list; \
	rm -f $$list || exit $$?; \
	test -n "$(EXEEXT)" || exit 0; \
	list=`for p in $$list; do echo "$$p"; done | sed 's/$(EXEEXT)$$//'`; \
	echo " rm -f" $$list; \
	rm -f $$list
SimpleWKTTester$(EXEEXT): $(SimpleWKTTester_OBJECTS) $(SimpleWKTTester_DEPENDENCIES) 
	@rm -f SimpleWKTTester$(EXEEXT)
	$(CXXLINK) $(SimpleWKTTester_OBJECTS) $(SimpleWKTTester_LDADD) $(LIBS)
XMLTester$(EXEEXT): $(XMLTester_OBJECTS) $(XMLTester_DEPENDENCIES) 
	@rm -f XMLTester$(EXEEXT)
	$(XMLTester_LINK) $(XMLTester_OBJECTS) $(XMLTester_LDADD) $(LIBS)

mostlyclean-compile:
	-rm -f *.$(OBJEXT)

distclean-compile:
	-rm -f *.tab.c

include ./$(DEPDIR)/SimpleWKTTester.Po
include ./$(DEPDIR)/XMLTester-BufferResultMatcher.Po
include ./$(DEPDIR)/XMLTester-SingleSidedBufferResultMatcher.Po
include ./$(DEPDIR)/XMLTester-XMLTester.Po
include ./$(DEPDIR)/XMLTester-tinystr.Po
include ./$(DEPDIR)/XMLTester-tinyxml.Po
include ./$(DEPDIR)/XMLTester-tinyxmlerror.Po
include ./$(DEPDIR)/XMLTester-tinyxmlparser.Po

.cpp.o:
	$(CXXCOMPILE) -MT $@ -MD -MP -MF $(DEPDIR)/$*.Tpo -c -o $@ $<
	$(am__mv) $(DEPDIR)/$*.Tpo $(DEPDIR)/$*.Po
#	source='$<' object='$@' libtool=no \
#	DEPDIR=$(DEPDIR) $(CXXDEPMODE) $(depcomp) \
#	$(CXXCOMPILE) -c -o $@ $<

.cpp.obj:
	$(CXXCOMPILE) -MT $@ -MD -MP -MF $(DEPDIR)/$*.Tpo -c -o $@ `$(CYGPATH_W) '$<'`
	$(am__mv) $(DEPDIR)/$*.Tpo $(DEPDIR)/$*.Po
#	source='$<' object='$@' libtool=no \
#	DEPDIR=$(DEPDIR) $(CXXDEPMODE) $(depcomp) \
#	$(CXXCOMPILE) -c -o $@ `$(CYGPATH_W) '$<'`

.cpp.lo:
	$(LTCXXCOMPILE) -MT $@ -MD -MP -MF $(DEPDIR)/$*.Tpo -c -o $@ $<
	$(am__mv) $(DEPDIR)/$*.Tpo $(DEPDIR)/$*.Plo
#	source='$<' object='$@' libtool=yes \
#	DEPDIR=$(DEPDIR) $(CXXDEPMODE) $(depcomp) \
#	$(LTCXXCOMPILE) -c -o $@ $<

XMLTester-XMLTester.o: XMLTester.cpp
	$(CXX) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(XMLTester_CXXFLAGS) $(CXXFLAGS) -MT XMLTester-XMLTester.o -MD -MP -MF $(DEPDIR)/XMLTester-XMLTester.Tpo -c -o XMLTester-XMLTester.o `test -f 'XMLTester.cpp' || echo '$(srcdir)/'`XMLTester.cpp
	$(am__mv) $(DEPDIR)/XMLTester-XMLTester.Tpo $(DEPDIR)/XMLTester-XMLTester.Po
#	source='XMLTester.cpp' object='XMLTester-XMLTester.o' libtool=no \
#	DEPDIR=$(DEPDIR) $(CXXDEPMODE) $(depcomp) \
#	$(CXX) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(XMLTester_CXXFLAGS) $(CXXFLAGS) -c -o XMLTester-XMLTester.o `test -f 'XMLTester.cpp' || echo '$(srcdir)/'`XMLTester.cpp

XMLTester-XMLTester.obj: XMLTester.cpp
	$(CXX) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(XMLTester_CXXFLAGS) $(CXXFLAGS) -MT XMLTester-XMLTester.obj -MD -MP -MF $(DEPDIR)/XMLTester-XMLTester.Tpo -c -o XMLTester-XMLTester.obj `if test -f 'XMLTester.cpp'; then $(CYGPATH_W) 'XMLTester.cpp'; else $(CYGPATH_W) '$(srcdir)/XMLTester.cpp'; fi`
	$(am__mv) $(DEPDIR)/XMLTester-XMLTester.Tpo $(DEPDIR)/XMLTester-XMLTester.Po
#	source='XMLTester.cpp' object='XMLTester-XMLTester.obj' libtool=no \
#	DEPDIR=$(DEPDIR) $(CXXDEPMODE) $(depcomp) \
#	$(CXX) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(XMLTester_CXXFLAGS) $(CXXFLAGS) -c -o XMLTester-XMLTester.obj `if test -f 'XMLTester.cpp'; then $(CYGPATH_W) 'XMLTester.cpp'; else $(CYGPATH_W) '$(srcdir)/XMLTester.cpp'; fi`

XMLTester-tinyxml.o: tinyxml/tinyxml.cpp
	$(CXX) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(XMLTester_CXXFLAGS) $(CXXFLAGS) -MT XMLTester-tinyxml.o -MD -MP -MF $(DEPDIR)/XMLTester-tinyxml.Tpo -c -o XMLTester-tinyxml.o `test -f 'tinyxml/tinyxml.cpp' || echo '$(srcdir)/'`tinyxml/tinyxml.cpp
	$(am__mv) $(DEPDIR)/XMLTester-tinyxml.Tpo $(DEPDIR)/XMLTester-tinyxml.Po
#	source='tinyxml/tinyxml.cpp' object='XMLTester-tinyxml.o' libtool=no \
#	DEPDIR=$(DEPDIR) $(CXXDEPMODE) $(depcomp) \
#	$(CXX) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(XMLTester_CXXFLAGS) $(CXXFLAGS) -c -o XMLTester-tinyxml.o `test -f 'tinyxml/tinyxml.cpp' || echo '$(srcdir)/'`tinyxml/tinyxml.cpp

XMLTester-tinyxml.obj: tinyxml/tinyxml.cpp
	$(CXX) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(XMLTester_CXXFLAGS) $(CXXFLAGS) -MT XMLTester-tinyxml.obj -MD -MP -MF $(DEPDIR)/XMLTester-tinyxml.Tpo -c -o XMLTester-tinyxml.obj `if test -f 'tinyxml/tinyxml.cpp'; then $(CYGPATH_W) 'tinyxml/tinyxml.cpp'; else $(CYGPATH_W) '$(srcdir)/tinyxml/tinyxml.cpp'; fi`
	$(am__mv) $(DEPDIR)/XMLTester-tinyxml.Tpo $(DEPDIR)/XMLTester-tinyxml.Po
#	source='tinyxml/tinyxml.cpp' object='XMLTester-tinyxml.obj' libtool=no \
#	DEPDIR=$(DEPDIR) $(CXXDEPMODE) $(depcomp) \
#	$(CXX) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(XMLTester_CXXFLAGS) $(CXXFLAGS) -c -o XMLTester-tinyxml.obj `if test -f 'tinyxml/tinyxml.cpp'; then $(CYGPATH_W) 'tinyxml/tinyxml.cpp'; else $(CYGPATH_W) '$(srcdir)/tinyxml/tinyxml.cpp'; fi`

XMLTester-tinystr.o: tinyxml/tinystr.cpp
	$(CXX) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(XMLTester_CXXFLAGS) $(CXXFLAGS) -MT XMLTester-tinystr.o -MD -MP -MF $(DEPDIR)/XMLTester-tinystr.Tpo -c -o XMLTester-tinystr.o `test -f 'tinyxml/tinystr.cpp' || echo '$(srcdir)/'`tinyxml/tinystr.cpp
	$(am__mv) $(DEPDIR)/XMLTester-tinystr.Tpo $(DEPDIR)/XMLTester-tinystr.Po
#	source='tinyxml/tinystr.cpp' object='XMLTester-tinystr.o' libtool=no \
#	DEPDIR=$(DEPDIR) $(CXXDEPMODE) $(depcomp) \
#	$(CXX) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(XMLTester_CXXFLAGS) $(CXXFLAGS) -c -o XMLTester-tinystr.o `test -f 'tinyxml/tinystr.cpp' || echo '$(srcdir)/'`tinyxml/tinystr.cpp

XMLTester-tinystr.obj: tinyxml/tinystr.cpp
	$(CXX) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(XMLTester_CXXFLAGS) $(CXXFLAGS) -MT XMLTester-tinystr.obj -MD -MP -MF $(DEPDIR)/XMLTester-tinystr.Tpo -c -o XMLTester-tinystr.obj `if test -f 'tinyxml/tinystr.cpp'; then $(CYGPATH_W) 'tinyxml/tinystr.cpp'; else $(CYGPATH_W) '$(srcdir)/tinyxml/tinystr.cpp'; fi`
	$(am__mv) $(DEPDIR)/XMLTester-tinystr.Tpo $(DEPDIR)/XMLTester-tinystr.Po
#	source='tinyxml/tinystr.cpp' object='XMLTester-tinystr.obj' libtool=no \
#	DEPDIR=$(DEPDIR) $(CXXDEPMODE) $(depcomp) \
#	$(CXX) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(XMLTester_CXXFLAGS) $(CXXFLAGS) -c -o XMLTester-tinystr.obj `if test -f 'tinyxml/tinystr.cpp'; then $(CYGPATH_W) 'tinyxml/tinystr.cpp'; else $(CYGPATH_W) '$(srcdir)/tinyxml/tinystr.cpp'; fi`

XMLTester-tinyxmlerror.o: tinyxml/tinyxmlerror.cpp
	$(CXX) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(XMLTester_CXXFLAGS) $(CXXFLAGS) -MT XMLTester-tinyxmlerror.o -MD -MP -MF $(DEPDIR)/XMLTester-tinyxmlerror.Tpo -c -o XMLTester-tinyxmlerror.o `test -f 'tinyxml/tinyxmlerror.cpp' || echo '$(srcdir)/'`tinyxml/tinyxmlerror.cpp
	$(am__mv) $(DEPDIR)/XMLTester-tinyxmlerror.Tpo $(DEPDIR)/XMLTester-tinyxmlerror.Po
#	source='tinyxml/tinyxmlerror.cpp' object='XMLTester-tinyxmlerror.o' libtool=no \
#	DEPDIR=$(DEPDIR) $(CXXDEPMODE) $(depcomp) \
#	$(CXX) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(XMLTester_CXXFLAGS) $(CXXFLAGS) -c -o XMLTester-tinyxmlerror.o `test -f 'tinyxml/tinyxmlerror.cpp' || echo '$(srcdir)/'`tinyxml/tinyxmlerror.cpp

XMLTester-tinyxmlerror.obj: tinyxml/tinyxmlerror.cpp
	$(CXX) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(XMLTester_CXXFLAGS) $(CXXFLAGS) -MT XMLTester-tinyxmlerror.obj -MD -MP -MF $(DEPDIR)/XMLTester-tinyxmlerror.Tpo -c -o XMLTester-tinyxmlerror.obj `if test -f 'tinyxml/tinyxmlerror.cpp'; then $(CYGPATH_W) 'tinyxml/tinyxmlerror.cpp'; else $(CYGPATH_W) '$(srcdir)/tinyxml/tinyxmlerror.cpp'; fi`
	$(am__mv) $(DEPDIR)/XMLTester-tinyxmlerror.Tpo $(DEPDIR)/XMLTester-tinyxmlerror.Po
#	source='tinyxml/tinyxmlerror.cpp' object='XMLTester-tinyxmlerror.obj' libtool=no \
#	DEPDIR=$(DEPDIR) $(CXXDEPMODE) $(depcomp) \
#	$(CXX) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(XMLTester_CXXFLAGS) $(CXXFLAGS) -c -o XMLTester-tinyxmlerror.obj `if test -f 'tinyxml/tinyxmlerror.cpp'; then $(CYGPATH_W) 'tinyxml/tinyxmlerror.cpp'; else $(CYGPATH_W) '$(srcdir)/tinyxml/tinyxmlerror.cpp'; fi`

XMLTester-tinyxmlparser.o: tinyxml/tinyxmlparser.cpp
	$(CXX) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(XMLTester_CXXFLAGS) $(CXXFLAGS) -MT XMLTester-tinyxmlparser.o -MD -MP -MF $(DEPDIR)/XMLTester-tinyxmlparser.Tpo -c -o XMLTester-tinyxmlparser.o `test -f 'tinyxml/tinyxmlparser.cpp' || echo '$(srcdir)/'`tinyxml/tinyxmlparser.cpp
	$(am__mv) $(DEPDIR)/XMLTester-tinyxmlparser.Tpo $(DEPDIR)/XMLTester-tinyxmlparser.Po
#	source='tinyxml/tinyxmlparser.cpp' object='XMLTester-tinyxmlparser.o' libtool=no \
#	DEPDIR=$(DEPDIR) $(CXXDEPMODE) $(depcomp) \
#	$(CXX) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(XMLTester_CXXFLAGS) $(CXXFLAGS) -c -o XMLTester-tinyxmlparser.o `test -f 'tinyxml/tinyxmlparser.cpp' || echo '$(srcdir)/'`tinyxml/tinyxmlparser.cpp

XMLTester-tinyxmlparser.obj: tinyxml/tinyxmlparser.cpp
	$(CXX) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(XMLTester_CXXFLAGS) $(CXXFLAGS) -MT XMLTester-tinyxmlparser.obj -MD -MP -MF $(DEPDIR)/XMLTester-tinyxmlparser.Tpo -c -o XMLTester-tinyxmlparser.obj `if test -f 'tinyxml/tinyxmlparser.cpp'; then $(CYGPATH_W) 'tinyxml/tinyxmlparser.cpp'; else $(CYGPATH_W) '$(srcdir)/tinyxml/tinyxmlparser.cpp'; fi`
	$(am__mv) $(DEPDIR)/XMLTester-tinyxmlparser.Tpo $(DEPDIR)/XMLTester-tinyxmlparser.Po
#	source='tinyxml/tinyxmlparser.cpp' object='XMLTester-tinyxmlparser.obj' libtool=no \
#	DEPDIR=$(DEPDIR) $(CXXDEPMODE) $(depcomp) \
#	$(CXX) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(XMLTester_CXXFLAGS) $(CXXFLAGS) -c -o XMLTester-tinyxmlparser.obj `if test -f 'tinyxml/tinyxmlparser.cpp'; then $(CYGPATH_W) 'tinyxml/tinyxmlparser.cpp'; else $(CYGPATH_W) '$(srcdir)/tinyxml/tinyxmlparser.cpp'; fi`

XMLTester-BufferResultMatcher.o: BufferResultMatcher.cpp
	$(CXX) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(XMLTester_CXXFLAGS) $(CXXFLAGS) -MT XMLTester-BufferResultMatcher.o -MD -MP -MF $(DEPDIR)/XMLTester-BufferResultMatcher.Tpo -c -o XMLTester-BufferResultMatcher.o `test -f 'BufferResultMatcher.cpp' || echo '$(srcdir)/'`BufferResultMatcher.cpp
	$(am__mv) $(DEPDIR)/XMLTester-BufferResultMatcher.Tpo $(DEPDIR)/XMLTester-BufferResultMatcher.Po
#	source='BufferResultMatcher.cpp' object='XMLTester-BufferResultMatcher.o' libtool=no \
#	DEPDIR=$(DEPDIR) $(CXXDEPMODE) $(depcomp) \
#	$(CXX) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(XMLTester_CXXFLAGS) $(CXXFLAGS) -c -o XMLTester-BufferResultMatcher.o `test -f 'BufferResultMatcher.cpp' || echo '$(srcdir)/'`BufferResultMatcher.cpp

XMLTester-BufferResultMatcher.obj: BufferResultMatcher.cpp
	$(CXX) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(XMLTester_CXXFLAGS) $(CXXFLAGS) -MT XMLTester-BufferResultMatcher.obj -MD -MP -MF $(DEPDIR)/XMLTester-BufferResultMatcher.Tpo -c -o XMLTester-BufferResultMatcher.obj `if test -f 'BufferResultMatcher.cpp'; then $(CYGPATH_W) 'BufferResultMatcher.cpp'; else $(CYGPATH_W) '$(srcdir)/BufferResultMatcher.cpp'; fi`
	$(am__mv) $(DEPDIR)/XMLTester-BufferResultMatcher.Tpo $(DEPDIR)/XMLTester-BufferResultMatcher.Po
#	source='BufferResultMatcher.cpp' object='XMLTester-BufferResultMatcher.obj' libtool=no \
#	DEPDIR=$(DEPDIR) $(CXXDEPMODE) $(depcomp) \
#	$(CXX) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(XMLTester_CXXFLAGS) $(CXXFLAGS) -c -o XMLTester-BufferResultMatcher.obj `if test -f 'BufferResultMatcher.cpp'; then $(CYGPATH_W) 'BufferResultMatcher.cpp'; else $(CYGPATH_W) '$(srcdir)/BufferResultMatcher.cpp'; fi`

XMLTester-SingleSidedBufferResultMatcher.o: SingleSidedBufferResultMatcher.cpp
	$(CXX) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(XMLTester_CXXFLAGS) $(CXXFLAGS) -MT XMLTester-SingleSidedBufferResultMatcher.o -MD -MP -MF $(DEPDIR)/XMLTester-SingleSidedBufferResultMatcher.Tpo -c -o XMLTester-SingleSidedBufferResultMatcher.o `test -f 'SingleSidedBufferResultMatcher.cpp' || echo '$(srcdir)/'`SingleSidedBufferResultMatcher.cpp
	$(am__mv) $(DEPDIR)/XMLTester-SingleSidedBufferResultMatcher.Tpo $(DEPDIR)/XMLTester-SingleSidedBufferResultMatcher.Po
#	source='SingleSidedBufferResultMatcher.cpp' object='XMLTester-SingleSidedBufferResultMatcher.o' libtool=no \
#	DEPDIR=$(DEPDIR) $(CXXDEPMODE) $(depcomp) \
#	$(CXX) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(XMLTester_CXXFLAGS) $(CXXFLAGS) -c -o XMLTester-SingleSidedBufferResultMatcher.o `test -f 'SingleSidedBufferResultMatcher.cpp' || echo '$(srcdir)/'`SingleSidedBufferResultMatcher.cpp

XMLTester-SingleSidedBufferResultMatcher.obj: SingleSidedBufferResultMatcher.cpp
	$(CXX) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(XMLTester_CXXFLAGS) $(CXXFLAGS) -MT XMLTester-SingleSidedBufferResultMatcher.obj -MD -MP -MF $(DEPDIR)/XMLTester-SingleSidedBufferResultMatcher.Tpo -c -o XMLTester-SingleSidedBufferResultMatcher.obj `if test -f 'SingleSidedBufferResultMatcher.cpp'; then $(CYGPATH_W) 'SingleSidedBufferResultMatcher.cpp'; else $(CYGPATH_W) '$(srcdir)/SingleSidedBufferResultMatcher.cpp'; fi`
	$(am__mv) $(DEPDIR)/XMLTester-SingleSidedBufferResultMatcher.Tpo $(DEPDIR)/XMLTester-SingleSidedBufferResultMatcher.Po
#	source='SingleSidedBufferResultMatcher.cpp' object='XMLTester-SingleSidedBufferResultMatcher.obj' libtool=no \
#	DEPDIR=$(DEPDIR) $(CXXDEPMODE) $(depcomp) \
#	$(CXX) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(XMLTester_CXXFLAGS) $(CXXFLAGS) -c -o XMLTester-SingleSidedBufferResultMatcher.obj `if test -f 'SingleSidedBufferResultMatcher.cpp'; then $(CYGPATH_W) 'SingleSidedBufferResultMatcher.cpp'; else $(CYGPATH_W) '$(srcdir)/SingleSidedBufferResultMatcher.cpp'; fi`

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

check-TESTS: $(TESTS)
	@failed=0; all=0; xfail=0; xpass=0; skip=0; \
	srcdir=$(srcdir); export srcdir; \
	list=' $(TESTS) '; \
	$(am__tty_colors); \
	if test -n "$$list"; then \
	  for tst in $$list; do \
	    if test -f ./$$tst; then dir=./; \
	    elif test -f $$tst; then dir=; \
	    else dir="$(srcdir)/"; fi; \
	    if $(TESTS_ENVIRONMENT) $${dir}$$tst; then \
	      all=`expr $$all + 1`; \
	      case " $(XFAIL_TESTS) " in \
	      *[\ \	]$$tst[\ \	]*) \
		xpass=`expr $$xpass + 1`; \
		failed=`expr $$failed + 1`; \
		col=$$red; res=XPASS; \
	      ;; \
	      *) \
		col=$$grn; res=PASS; \
	      ;; \
	      esac; \
	    elif test $$? -ne 77; then \
	      all=`expr $$all + 1`; \
	      case " $(XFAIL_TESTS) " in \
	      *[\ \	]$$tst[\ \	]*) \
		xfail=`expr $$xfail + 1`; \
		col=$$lgn; res=XFAIL; \
	      ;; \
	      *) \
		failed=`expr $$failed + 1`; \
		col=$$red; res=FAIL; \
	      ;; \
	      esac; \
	    else \
	      skip=`expr $$skip + 1`; \
	      col=$$blu; res=SKIP; \
	    fi; \
	    echo "$${col}$$res$${std}: $$tst"; \
	  done; \
	  if test "$$all" -eq 1; then \
	    tests="test"; \
	    All=""; \
	  else \
	    tests="tests"; \
	    All="All "; \
	  fi; \
	  if test "$$failed" -eq 0; then \
	    if test "$$xfail" -eq 0; then \
	      banner="$$All$$all $$tests passed"; \
	    else \
	      if test "$$xfail" -eq 1; then failures=failure; else failures=failures; fi; \
	      banner="$$All$$all $$tests behaved as expected ($$xfail expected $$failures)"; \
	    fi; \
	  else \
	    if test "$$xpass" -eq 0; then \
	      banner="$$failed of $$all $$tests failed"; \
	    else \
	      if test "$$xpass" -eq 1; then passes=pass; else passes=passes; fi; \
	      banner="$$failed of $$all $$tests did not behave as expected ($$xpass unexpected $$passes)"; \
	    fi; \
	  fi; \
	  dashes="$$banner"; \
	  skipped=""; \
	  if test "$$skip" -ne 0; then \
	    if test "$$skip" -eq 1; then \
	      skipped="($$skip test was not run)"; \
	    else \
	      skipped="($$skip tests were not run)"; \
	    fi; \
	    test `echo "$$skipped" | wc -c` -le `echo "$$banner" | wc -c` || \
	      dashes="$$skipped"; \
	  fi; \
	  report=""; \
	  if test "$$failed" -ne 0 && test -n "$(PACKAGE_BUGREPORT)"; then \
	    report="Please report to $(PACKAGE_BUGREPORT)"; \
	    test `echo "$$report" | wc -c` -le `echo "$$banner" | wc -c` || \
	      dashes="$$report"; \
	  fi; \
	  dashes=`echo "$$dashes" | sed s/./=/g`; \
	  if test "$$failed" -eq 0; then \
	    echo "$$grn$$dashes"; \
	  else \
	    echo "$$red$$dashes"; \
	  fi; \
	  echo "$$banner"; \
	  test -z "$$skipped" || echo "$$skipped"; \
	  test -z "$$report" || echo "$$report"; \
	  echo "$$dashes$$std"; \
	  test "$$failed" -eq 0; \
	else :; fi

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
	$(MAKE) $(AM_MAKEFLAGS) check-TESTS
check: check-am
all-am: Makefile $(PROGRAMS)
installdirs:
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
	-test -z "$(CLEANFILES)" || rm -f $(CLEANFILES)

distclean-generic:
	-test -z "$(CONFIG_CLEAN_FILES)" || rm -f $(CONFIG_CLEAN_FILES)
	-test . = "$(srcdir)" || test -z "$(CONFIG_CLEAN_VPATH_FILES)" || rm -f $(CONFIG_CLEAN_VPATH_FILES)

maintainer-clean-generic:
	@echo "This command is intended for maintainers to use"
	@echo "it deletes files that may require special tools to rebuild."
clean: clean-am

clean-am: clean-generic clean-libtool clean-noinstPROGRAMS \
	mostlyclean-am

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

install-exec-am:

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

uninstall-am:

.MAKE: check-am install-am install-strip

.PHONY: CTAGS GTAGS all all-am check check-TESTS check-am clean \
	clean-generic clean-libtool clean-noinstPROGRAMS ctags \
	distclean distclean-compile distclean-generic \
	distclean-libtool distclean-tags distdir dvi dvi-am html \
	html-am info info-am install install-am install-data \
	install-data-am install-dvi install-dvi-am install-exec \
	install-exec-am install-html install-html-am install-info \
	install-info-am install-man install-pdf install-pdf-am \
	install-ps install-ps-am install-strip installcheck \
	installcheck-am installdirs maintainer-clean \
	maintainer-clean-generic mostlyclean mostlyclean-compile \
	mostlyclean-generic mostlyclean-libtool pdf pdf-am ps ps-am \
	tags uninstall uninstall-am


static:
	$(CXX) $(CXXFLAGS) -I../include -o staticXMLTester XMLTester.cpp MarkupSTL.o ../../src/geom/.libs/libgeos.a

testrunner: testrunner.sh Makefile
	@sh $(srcdir)/testrunner.sh $@ --test-valid-output $(SAFE_XMLTESTS)

# Tell versions [3.59,3.63) of GNU make to not export all variables.
# Otherwise a system limit (for SysV at least) may be exceeded.
.NOEXPORT:
