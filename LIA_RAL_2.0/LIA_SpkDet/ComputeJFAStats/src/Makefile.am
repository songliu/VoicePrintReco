bin_PROGRAMS=ComputeJFAStats
ComputeJFAStats_SOURCES= \
	ComputeJFAStats.cpp\
	ComputeJFAStatsMain.cpp

ComputeJFAStats_CPPFLAGS=-I../include -I$(top_srcdir)/LIA_SpkTools/include -I$(ALIZE_PATH)/include
ComputeJFAStats_LDFLAGS=-L$(top_srcdir)/lib -L$(ALIZE_PATH)/lib
ComputeJFAStats_LDADD=-lliatools_${OS}_${ARCH}${DEBUG} $(lib_alize) $(LIBTHREAD)

all:
	mv ${bin_PROGRAMS} ${top_srcdir}/bin
