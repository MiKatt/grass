
MODULE_TOPDIR = ../..

PGM = d.vect

LIBES = $(DISPLAYLIB) $(SYMBLIB) $(VECTORLIB) $(DBMILIB) $(RASTERLIB) $(GISLIB)
DEPENDENCIES = $(DISPLAYDEP) $(SYMBDEP) $(VECTORDEP) $(DBMIDEP) $(RASTERDEP) $(GISDEP)

EXTRA_INC = $(VECT_INC)
EXTRA_CFLAGS = $(VECT_CFLAGS)

include $(MODULE_TOPDIR)/include/Make/Module.make

default: cmd
