# This file was automatically generated by bakefile.
#
# Any manual changes will be lost if it is regenerated,
# modify the source .bkl file instead if possible.

# You may define standard make variables such as CFLAGS or
# CXXFLAGS to affect the build. For example, you could use:
#
#      make CXXFLAGS=-g
#
# to build with debug information. The full list of variables
# that can be used by this makefile is:
# AR, CC, CFLAGS, CPPFLAGS, CXX, CXXFLAGS, LD, LDFLAGS, MAKE, RANLIB.

# You may also specify config=Debug|Release
# or their corresponding lower case variants on make command line to select
# the corresponding default flags values.
ifeq ($(config),debug)
override config := Debug
endif
ifeq ($(config),release)
override config := Release
endif
ifeq ($(config),Debug)
override CPPFLAGS += -DDEBUG
override CFLAGS += -g -O0
override CXXFLAGS += -g -O0
override LDFLAGS += -g
else ifeq ($(config),Release)
override CPPFLAGS += -DNDEBUG
override CFLAGS += -O2
override CXXFLAGS += -O2
else ifneq (,$(config))
$(warning Unknown configuration "$(config)")
endif
#
# Additionally, this makefile is customizable with the following
# settings:
#
#      WXWIDGETS_ROOT  Path to the WxWidgets installation

# Use "make RANLIB=''" for platforms without ranlib.
RANLIB ?= ranlib

CC := cc
CXX := c++

_true  := true
_false :=
_not    = $(if $(1),$(_false),$(_true_))
_equal  = $(and $(findstring $(1),$(2)),$(findstring $(2),$(1)))


# The directory for the build files, may be overridden on make command line.
builddir = .

ifneq ($(builddir),.)
_builddir := $(if $(findstring $(abspath $(builddir)),$(builddir)),,../../)$(builddir)/../../
_builddir_error := $(shell mkdir -p $(_builddir) 2>&1)
$(if $(_builddir_error),$(error Failed to create build directory: $(_builddir_error)))
endif

# ------------
# Configurable settings:
# 

# Path to the WxWidgets installation
WXWIDGETS_ROOT ?= $(WXWIN)

# ------------

all: $(_builddir)build/bakefiles/../../lib$(if $(call _equal,$(config),Debug),wxchartsd,wxcharts).a

$(_builddir)build/bakefiles/../../lib$(if $(call _equal,$(config),Debug),wxchartsd,wxcharts).a: $(_builddir)wxcharts_wxchartutilities.o $(_builddir)wxcharts_wxchartpadding.o $(_builddir)wxcharts_wxchartelement.o $(_builddir)wxcharts_wxchartbackgroundoptions.o $(_builddir)wxcharts_wxchartbackground.o $(_builddir)wxcharts_wxchartfontoptions.o $(_builddir)wxcharts_wxchartlabel.o $(_builddir)wxcharts_wxchartlabeloptions.o $(_builddir)wxcharts_wxchartlabelgroup.o $(_builddir)wxcharts_wxchartaxis.o $(_builddir)wxcharts_wxchartaxisoptions.o $(_builddir)wxcharts_wxchartnumericalaxis.o $(_builddir)wxcharts_wxchartgridmapping.o $(_builddir)wxcharts_wxchartgridoptions.o $(_builddir)wxcharts_wxchartgrid.o $(_builddir)wxcharts_wxchartradialgridoptions.o $(_builddir)wxcharts_wxchartradialgrid.o $(_builddir)wxcharts_wxchartpointoptions.o $(_builddir)wxcharts_wxchartpoint.o $(_builddir)wxcharts_wxchartrectangleoptions.o $(_builddir)wxcharts_wxchartrectangle.o $(_builddir)wxcharts_wxchartarc.o $(_builddir)wxcharts_wxchartarcoptions.o $(_builddir)wxcharts_wxcharttooltipoptions.o $(_builddir)wxcharts_wxcharttooltipprovider.o $(_builddir)wxcharts_wxcharttooltip.o $(_builddir)wxcharts_wxchartmultitooltipoptions.o $(_builddir)wxcharts_wxchartmultitooltip.o $(_builddir)wxcharts_wxchartlegendlineoptions.o $(_builddir)wxcharts_wxchartlegendline.o $(_builddir)wxcharts_wxchartlegendoptions.o $(_builddir)wxcharts_wxchartlegendctrl.o $(_builddir)wxcharts_wxchartslicedata.o $(_builddir)wxcharts_wxchartohlcdata.o $(_builddir)wxcharts_wxchartoptions.o $(_builddir)wxcharts_wxchartctrl.o $(_builddir)wxcharts_wxbarchartdata.o $(_builddir)wxcharts_wxbarchartoptions.o $(_builddir)wxcharts_wxbarchartctrl.o $(_builddir)wxcharts_wxcandlestickchartoptions.o $(_builddir)wxcharts_wxcandlestickchartctrl.o $(_builddir)wxcharts_wxcolumnchartoptions.o $(_builddir)wxcharts_wxcolumnchartctrl.o $(_builddir)wxcharts_wxstackedbarchartoptions.o $(_builddir)wxcharts_wxstackedbarchartctrl.o $(_builddir)wxcharts_wxstackedcolumnchartoptions.o $(_builddir)wxcharts_wxstackedcolumnchartctrl.o $(_builddir)wxcharts_wxlinechartoptions.o $(_builddir)wxcharts_wxlinechartctrl.o $(_builddir)wxcharts_wxdoughnutandpiechartoptionsbase.o $(_builddir)wxcharts_wxdoughnutandpiechartbase.o $(_builddir)wxcharts_wxdoughnutchartoptions.o $(_builddir)wxcharts_wxdoughnutchartctrl.o $(_builddir)wxcharts_wxohlcchartoptions.o $(_builddir)wxcharts_wxohlcchartctrl.o $(_builddir)wxcharts_wxpiechartoptions.o $(_builddir)wxcharts_wxpiechartctrl.o $(_builddir)wxcharts_wxpolarareachartoptions.o $(_builddir)wxcharts_wxpolarareachartctrl.o $(_builddir)wxcharts_wxradarchartoptions.o $(_builddir)wxcharts_wxradarchartctrl.o $(_builddir)wxcharts_wxscatterplotoptions.o $(_builddir)wxcharts_wxscatterplotctrl.o $(_builddir)wxcharts_wxbubblechartoptions.o $(_builddir)wxcharts_wxbubblechartctrl.o
	$(AR) rcu $@ $(_builddir)wxcharts_wxchartutilities.o $(_builddir)wxcharts_wxchartpadding.o $(_builddir)wxcharts_wxchartelement.o $(_builddir)wxcharts_wxchartbackgroundoptions.o $(_builddir)wxcharts_wxchartbackground.o $(_builddir)wxcharts_wxchartfontoptions.o $(_builddir)wxcharts_wxchartlabel.o $(_builddir)wxcharts_wxchartlabeloptions.o $(_builddir)wxcharts_wxchartlabelgroup.o $(_builddir)wxcharts_wxchartaxis.o $(_builddir)wxcharts_wxchartaxisoptions.o $(_builddir)wxcharts_wxchartnumericalaxis.o $(_builddir)wxcharts_wxchartgridmapping.o $(_builddir)wxcharts_wxchartgridoptions.o $(_builddir)wxcharts_wxchartgrid.o $(_builddir)wxcharts_wxchartradialgridoptions.o $(_builddir)wxcharts_wxchartradialgrid.o $(_builddir)wxcharts_wxchartpointoptions.o $(_builddir)wxcharts_wxchartpoint.o $(_builddir)wxcharts_wxchartrectangleoptions.o $(_builddir)wxcharts_wxchartrectangle.o $(_builddir)wxcharts_wxchartarc.o $(_builddir)wxcharts_wxchartarcoptions.o $(_builddir)wxcharts_wxcharttooltipoptions.o $(_builddir)wxcharts_wxcharttooltipprovider.o $(_builddir)wxcharts_wxcharttooltip.o $(_builddir)wxcharts_wxchartmultitooltipoptions.o $(_builddir)wxcharts_wxchartmultitooltip.o $(_builddir)wxcharts_wxchartlegendlineoptions.o $(_builddir)wxcharts_wxchartlegendline.o $(_builddir)wxcharts_wxchartlegendoptions.o $(_builddir)wxcharts_wxchartlegendctrl.o $(_builddir)wxcharts_wxchartslicedata.o $(_builddir)wxcharts_wxchartohlcdata.o $(_builddir)wxcharts_wxchartoptions.o $(_builddir)wxcharts_wxchartctrl.o $(_builddir)wxcharts_wxbarchartdata.o $(_builddir)wxcharts_wxbarchartoptions.o $(_builddir)wxcharts_wxbarchartctrl.o $(_builddir)wxcharts_wxcandlestickchartoptions.o $(_builddir)wxcharts_wxcandlestickchartctrl.o $(_builddir)wxcharts_wxcolumnchartoptions.o $(_builddir)wxcharts_wxcolumnchartctrl.o $(_builddir)wxcharts_wxstackedbarchartoptions.o $(_builddir)wxcharts_wxstackedbarchartctrl.o $(_builddir)wxcharts_wxstackedcolumnchartoptions.o $(_builddir)wxcharts_wxstackedcolumnchartctrl.o $(_builddir)wxcharts_wxlinechartoptions.o $(_builddir)wxcharts_wxlinechartctrl.o $(_builddir)wxcharts_wxdoughnutandpiechartoptionsbase.o $(_builddir)wxcharts_wxdoughnutandpiechartbase.o $(_builddir)wxcharts_wxdoughnutchartoptions.o $(_builddir)wxcharts_wxdoughnutchartctrl.o $(_builddir)wxcharts_wxohlcchartoptions.o $(_builddir)wxcharts_wxohlcchartctrl.o $(_builddir)wxcharts_wxpiechartoptions.o $(_builddir)wxcharts_wxpiechartctrl.o $(_builddir)wxcharts_wxpolarareachartoptions.o $(_builddir)wxcharts_wxpolarareachartctrl.o $(_builddir)wxcharts_wxradarchartoptions.o $(_builddir)wxcharts_wxradarchartctrl.o $(_builddir)wxcharts_wxscatterplotoptions.o $(_builddir)wxcharts_wxscatterplotctrl.o $(_builddir)wxcharts_wxbubblechartoptions.o $(_builddir)wxcharts_wxbubblechartctrl.o
	$(RANLIB) $@

$(_builddir)wxcharts_wxchartutilities.o: src/wxchartutilities.cpp
	$(CXX) -c -o $@ $(CPPFLAGS) $(CXXFLAGS) -MD -MP -fPIC -DPIC -pthread -Iinclude/wx/charts `wx-config --cxxflags --libs` src/wxchartutilities.cpp

$(_builddir)wxcharts_wxchartpadding.o: src/wxchartpadding.cpp
	$(CXX) -c -o $@ $(CPPFLAGS) $(CXXFLAGS) -MD -MP -fPIC -DPIC -pthread -Iinclude/wx/charts `wx-config --cxxflags --libs` src/wxchartpadding.cpp

$(_builddir)wxcharts_wxchartelement.o: src/wxchartelement.cpp
	$(CXX) -c -o $@ $(CPPFLAGS) $(CXXFLAGS) -MD -MP -fPIC -DPIC -pthread -Iinclude/wx/charts `wx-config --cxxflags --libs` src/wxchartelement.cpp

$(_builddir)wxcharts_wxchartbackgroundoptions.o: src/wxchartbackgroundoptions.cpp
	$(CXX) -c -o $@ $(CPPFLAGS) $(CXXFLAGS) -MD -MP -fPIC -DPIC -pthread -Iinclude/wx/charts `wx-config --cxxflags --libs` src/wxchartbackgroundoptions.cpp

$(_builddir)wxcharts_wxchartbackground.o: src/wxchartbackground.cpp
	$(CXX) -c -o $@ $(CPPFLAGS) $(CXXFLAGS) -MD -MP -fPIC -DPIC -pthread -Iinclude/wx/charts `wx-config --cxxflags --libs` src/wxchartbackground.cpp

$(_builddir)wxcharts_wxchartfontoptions.o: src/wxchartfontoptions.cpp
	$(CXX) -c -o $@ $(CPPFLAGS) $(CXXFLAGS) -MD -MP -fPIC -DPIC -pthread -Iinclude/wx/charts `wx-config --cxxflags --libs` src/wxchartfontoptions.cpp

$(_builddir)wxcharts_wxchartlabel.o: src/wxchartlabel.cpp
	$(CXX) -c -o $@ $(CPPFLAGS) $(CXXFLAGS) -MD -MP -fPIC -DPIC -pthread -Iinclude/wx/charts `wx-config --cxxflags --libs` src/wxchartlabel.cpp

$(_builddir)wxcharts_wxchartlabeloptions.o: src/wxchartlabeloptions.cpp
	$(CXX) -c -o $@ $(CPPFLAGS) $(CXXFLAGS) -MD -MP -fPIC -DPIC -pthread -Iinclude/wx/charts `wx-config --cxxflags --libs` src/wxchartlabeloptions.cpp

$(_builddir)wxcharts_wxchartlabelgroup.o: src/wxchartlabelgroup.cpp
	$(CXX) -c -o $@ $(CPPFLAGS) $(CXXFLAGS) -MD -MP -fPIC -DPIC -pthread -Iinclude/wx/charts `wx-config --cxxflags --libs` src/wxchartlabelgroup.cpp

$(_builddir)wxcharts_wxchartaxis.o: src/wxchartaxis.cpp
	$(CXX) -c -o $@ $(CPPFLAGS) $(CXXFLAGS) -MD -MP -fPIC -DPIC -pthread -Iinclude/wx/charts `wx-config --cxxflags --libs` src/wxchartaxis.cpp

$(_builddir)wxcharts_wxchartaxisoptions.o: src/wxchartaxisoptions.cpp
	$(CXX) -c -o $@ $(CPPFLAGS) $(CXXFLAGS) -MD -MP -fPIC -DPIC -pthread -Iinclude/wx/charts `wx-config --cxxflags --libs` src/wxchartaxisoptions.cpp

$(_builddir)wxcharts_wxchartnumericalaxis.o: src/wxchartnumericalaxis.cpp
	$(CXX) -c -o $@ $(CPPFLAGS) $(CXXFLAGS) -MD -MP -fPIC -DPIC -pthread -Iinclude/wx/charts `wx-config --cxxflags --libs` src/wxchartnumericalaxis.cpp

$(_builddir)wxcharts_wxchartgridmapping.o: src/wxchartgridmapping.cpp
	$(CXX) -c -o $@ $(CPPFLAGS) $(CXXFLAGS) -MD -MP -fPIC -DPIC -pthread -Iinclude/wx/charts `wx-config --cxxflags --libs` src/wxchartgridmapping.cpp

$(_builddir)wxcharts_wxchartgridoptions.o: src/wxchartgridoptions.cpp
	$(CXX) -c -o $@ $(CPPFLAGS) $(CXXFLAGS) -MD -MP -fPIC -DPIC -pthread -Iinclude/wx/charts `wx-config --cxxflags --libs` src/wxchartgridoptions.cpp

$(_builddir)wxcharts_wxchartgrid.o: src/wxchartgrid.cpp
	$(CXX) -c -o $@ $(CPPFLAGS) $(CXXFLAGS) -MD -MP -fPIC -DPIC -pthread -Iinclude/wx/charts `wx-config --cxxflags --libs` src/wxchartgrid.cpp

$(_builddir)wxcharts_wxchartradialgridoptions.o: src/wxchartradialgridoptions.cpp
	$(CXX) -c -o $@ $(CPPFLAGS) $(CXXFLAGS) -MD -MP -fPIC -DPIC -pthread -Iinclude/wx/charts `wx-config --cxxflags --libs` src/wxchartradialgridoptions.cpp

$(_builddir)wxcharts_wxchartradialgrid.o: src/wxchartradialgrid.cpp
	$(CXX) -c -o $@ $(CPPFLAGS) $(CXXFLAGS) -MD -MP -fPIC -DPIC -pthread -Iinclude/wx/charts `wx-config --cxxflags --libs` src/wxchartradialgrid.cpp

$(_builddir)wxcharts_wxchartpointoptions.o: src/wxchartpointoptions.cpp
	$(CXX) -c -o $@ $(CPPFLAGS) $(CXXFLAGS) -MD -MP -fPIC -DPIC -pthread -Iinclude/wx/charts `wx-config --cxxflags --libs` src/wxchartpointoptions.cpp

$(_builddir)wxcharts_wxchartpoint.o: src/wxchartpoint.cpp
	$(CXX) -c -o $@ $(CPPFLAGS) $(CXXFLAGS) -MD -MP -fPIC -DPIC -pthread -Iinclude/wx/charts `wx-config --cxxflags --libs` src/wxchartpoint.cpp

$(_builddir)wxcharts_wxchartrectangleoptions.o: src/wxchartrectangleoptions.cpp
	$(CXX) -c -o $@ $(CPPFLAGS) $(CXXFLAGS) -MD -MP -fPIC -DPIC -pthread -Iinclude/wx/charts `wx-config --cxxflags --libs` src/wxchartrectangleoptions.cpp

$(_builddir)wxcharts_wxchartrectangle.o: src/wxchartrectangle.cpp
	$(CXX) -c -o $@ $(CPPFLAGS) $(CXXFLAGS) -MD -MP -fPIC -DPIC -pthread -Iinclude/wx/charts `wx-config --cxxflags --libs` src/wxchartrectangle.cpp

$(_builddir)wxcharts_wxchartarc.o: src/wxchartarc.cpp
	$(CXX) -c -o $@ $(CPPFLAGS) $(CXXFLAGS) -MD -MP -fPIC -DPIC -pthread -Iinclude/wx/charts `wx-config --cxxflags --libs` src/wxchartarc.cpp

$(_builddir)wxcharts_wxchartarcoptions.o: src/wxchartarcoptions.cpp
	$(CXX) -c -o $@ $(CPPFLAGS) $(CXXFLAGS) -MD -MP -fPIC -DPIC -pthread -Iinclude/wx/charts `wx-config --cxxflags --libs` src/wxchartarcoptions.cpp

$(_builddir)wxcharts_wxcharttooltipoptions.o: src/wxcharttooltipoptions.cpp
	$(CXX) -c -o $@ $(CPPFLAGS) $(CXXFLAGS) -MD -MP -fPIC -DPIC -pthread -Iinclude/wx/charts `wx-config --cxxflags --libs` src/wxcharttooltipoptions.cpp

$(_builddir)wxcharts_wxcharttooltipprovider.o: src/wxcharttooltipprovider.cpp
	$(CXX) -c -o $@ $(CPPFLAGS) $(CXXFLAGS) -MD -MP -fPIC -DPIC -pthread -Iinclude/wx/charts `wx-config --cxxflags --libs` src/wxcharttooltipprovider.cpp

$(_builddir)wxcharts_wxcharttooltip.o: src/wxcharttooltip.cpp
	$(CXX) -c -o $@ $(CPPFLAGS) $(CXXFLAGS) -MD -MP -fPIC -DPIC -pthread -Iinclude/wx/charts `wx-config --cxxflags --libs` src/wxcharttooltip.cpp

$(_builddir)wxcharts_wxchartmultitooltipoptions.o: src/wxchartmultitooltipoptions.cpp
	$(CXX) -c -o $@ $(CPPFLAGS) $(CXXFLAGS) -MD -MP -fPIC -DPIC -pthread -Iinclude/wx/charts `wx-config --cxxflags --libs` src/wxchartmultitooltipoptions.cpp

$(_builddir)wxcharts_wxchartmultitooltip.o: src/wxchartmultitooltip.cpp
	$(CXX) -c -o $@ $(CPPFLAGS) $(CXXFLAGS) -MD -MP -fPIC -DPIC -pthread -Iinclude/wx/charts `wx-config --cxxflags --libs` src/wxchartmultitooltip.cpp

$(_builddir)wxcharts_wxchartlegendlineoptions.o: src/wxchartlegendlineoptions.cpp
	$(CXX) -c -o $@ $(CPPFLAGS) $(CXXFLAGS) -MD -MP -fPIC -DPIC -pthread -Iinclude/wx/charts `wx-config --cxxflags --libs` src/wxchartlegendlineoptions.cpp

$(_builddir)wxcharts_wxchartlegendline.o: src/wxchartlegendline.cpp
	$(CXX) -c -o $@ $(CPPFLAGS) $(CXXFLAGS) -MD -MP -fPIC -DPIC -pthread -Iinclude/wx/charts `wx-config --cxxflags --libs` src/wxchartlegendline.cpp

$(_builddir)wxcharts_wxchartlegendoptions.o: src/wxchartlegendoptions.cpp
	$(CXX) -c -o $@ $(CPPFLAGS) $(CXXFLAGS) -MD -MP -fPIC -DPIC -pthread -Iinclude/wx/charts `wx-config --cxxflags --libs` src/wxchartlegendoptions.cpp

$(_builddir)wxcharts_wxchartlegendctrl.o: src/wxchartlegendctrl.cpp
	$(CXX) -c -o $@ $(CPPFLAGS) $(CXXFLAGS) -MD -MP -fPIC -DPIC -pthread -Iinclude/wx/charts `wx-config --cxxflags --libs` src/wxchartlegendctrl.cpp

$(_builddir)wxcharts_wxchartslicedata.o: src/wxchartslicedata.cpp
	$(CXX) -c -o $@ $(CPPFLAGS) $(CXXFLAGS) -MD -MP -fPIC -DPIC -pthread -Iinclude/wx/charts `wx-config --cxxflags --libs` src/wxchartslicedata.cpp

$(_builddir)wxcharts_wxchartohlcdata.o: src/wxchartohlcdata.cpp
	$(CXX) -c -o $@ $(CPPFLAGS) $(CXXFLAGS) -MD -MP -fPIC -DPIC -pthread -Iinclude/wx/charts `wx-config --cxxflags --libs` src/wxchartohlcdata.cpp

$(_builddir)wxcharts_wxchartoptions.o: src/wxchartoptions.cpp
	$(CXX) -c -o $@ $(CPPFLAGS) $(CXXFLAGS) -MD -MP -fPIC -DPIC -pthread -Iinclude/wx/charts `wx-config --cxxflags --libs` src/wxchartoptions.cpp

$(_builddir)wxcharts_wxchartctrl.o: src/wxchartctrl.cpp
	$(CXX) -c -o $@ $(CPPFLAGS) $(CXXFLAGS) -MD -MP -fPIC -DPIC -pthread -Iinclude/wx/charts `wx-config --cxxflags --libs` src/wxchartctrl.cpp

$(_builddir)wxcharts_wxbarchartdata.o: src/wxbarchartdata.cpp
	$(CXX) -c -o $@ $(CPPFLAGS) $(CXXFLAGS) -MD -MP -fPIC -DPIC -pthread -Iinclude/wx/charts `wx-config --cxxflags --libs` src/wxbarchartdata.cpp

$(_builddir)wxcharts_wxbarchartoptions.o: src/wxbarchartoptions.cpp
	$(CXX) -c -o $@ $(CPPFLAGS) $(CXXFLAGS) -MD -MP -fPIC -DPIC -pthread -Iinclude/wx/charts `wx-config --cxxflags --libs` src/wxbarchartoptions.cpp

$(_builddir)wxcharts_wxbarchartctrl.o: src/wxbarchartctrl.cpp
	$(CXX) -c -o $@ $(CPPFLAGS) $(CXXFLAGS) -MD -MP -fPIC -DPIC -pthread -Iinclude/wx/charts `wx-config --cxxflags --libs` src/wxbarchartctrl.cpp

$(_builddir)wxcharts_wxcandlestickchartoptions.o: src/wxcandlestickchartoptions.cpp
	$(CXX) -c -o $@ $(CPPFLAGS) $(CXXFLAGS) -MD -MP -fPIC -DPIC -pthread -Iinclude/wx/charts `wx-config --cxxflags --libs` src/wxcandlestickchartoptions.cpp

$(_builddir)wxcharts_wxcandlestickchartctrl.o: src/wxcandlestickchartctrl.cpp
	$(CXX) -c -o $@ $(CPPFLAGS) $(CXXFLAGS) -MD -MP -fPIC -DPIC -pthread -Iinclude/wx/charts `wx-config --cxxflags --libs` src/wxcandlestickchartctrl.cpp

$(_builddir)wxcharts_wxcolumnchartoptions.o: src/wxcolumnchartoptions.cpp
	$(CXX) -c -o $@ $(CPPFLAGS) $(CXXFLAGS) -MD -MP -fPIC -DPIC -pthread -Iinclude/wx/charts `wx-config --cxxflags --libs` src/wxcolumnchartoptions.cpp

$(_builddir)wxcharts_wxcolumnchartctrl.o: src/wxcolumnchartctrl.cpp
	$(CXX) -c -o $@ $(CPPFLAGS) $(CXXFLAGS) -MD -MP -fPIC -DPIC -pthread -Iinclude/wx/charts `wx-config --cxxflags --libs` src/wxcolumnchartctrl.cpp

$(_builddir)wxcharts_wxstackedbarchartoptions.o: src/wxstackedbarchartoptions.cpp
	$(CXX) -c -o $@ $(CPPFLAGS) $(CXXFLAGS) -MD -MP -fPIC -DPIC -pthread -Iinclude/wx/charts `wx-config --cxxflags --libs` src/wxstackedbarchartoptions.cpp

$(_builddir)wxcharts_wxstackedbarchartctrl.o: src/wxstackedbarchartctrl.cpp
	$(CXX) -c -o $@ $(CPPFLAGS) $(CXXFLAGS) -MD -MP -fPIC -DPIC -pthread -Iinclude/wx/charts `wx-config --cxxflags --libs` src/wxstackedbarchartctrl.cpp

$(_builddir)wxcharts_wxstackedcolumnchartoptions.o: src/wxstackedcolumnchartoptions.cpp
	$(CXX) -c -o $@ $(CPPFLAGS) $(CXXFLAGS) -MD -MP -fPIC -DPIC -pthread -Iinclude/wx/charts `wx-config --cxxflags --libs` src/wxstackedcolumnchartoptions.cpp

$(_builddir)wxcharts_wxstackedcolumnchartctrl.o: src/wxstackedcolumnchartctrl.cpp
	$(CXX) -c -o $@ $(CPPFLAGS) $(CXXFLAGS) -MD -MP -fPIC -DPIC -pthread -Iinclude/wx/charts `wx-config --cxxflags --libs` src/wxstackedcolumnchartctrl.cpp

$(_builddir)wxcharts_wxlinechartoptions.o: src/wxlinechartoptions.cpp
	$(CXX) -c -o $@ $(CPPFLAGS) $(CXXFLAGS) -MD -MP -fPIC -DPIC -pthread -Iinclude/wx/charts `wx-config --cxxflags --libs` src/wxlinechartoptions.cpp

$(_builddir)wxcharts_wxlinechartctrl.o: src/wxlinechartctrl.cpp
	$(CXX) -c -o $@ $(CPPFLAGS) $(CXXFLAGS) -MD -MP -fPIC -DPIC -pthread -Iinclude/wx/charts `wx-config --cxxflags --libs` src/wxlinechartctrl.cpp

$(_builddir)wxcharts_wxdoughnutandpiechartoptionsbase.o: src/wxdoughnutandpiechartoptionsbase.cpp
	$(CXX) -c -o $@ $(CPPFLAGS) $(CXXFLAGS) -MD -MP -fPIC -DPIC -pthread -Iinclude/wx/charts `wx-config --cxxflags --libs` src/wxdoughnutandpiechartoptionsbase.cpp

$(_builddir)wxcharts_wxdoughnutandpiechartbase.o: src/wxdoughnutandpiechartbase.cpp
	$(CXX) -c -o $@ $(CPPFLAGS) $(CXXFLAGS) -MD -MP -fPIC -DPIC -pthread -Iinclude/wx/charts `wx-config --cxxflags --libs` src/wxdoughnutandpiechartbase.cpp

$(_builddir)wxcharts_wxdoughnutchartoptions.o: src/wxdoughnutchartoptions.cpp
	$(CXX) -c -o $@ $(CPPFLAGS) $(CXXFLAGS) -MD -MP -fPIC -DPIC -pthread -Iinclude/wx/charts `wx-config --cxxflags --libs` src/wxdoughnutchartoptions.cpp

$(_builddir)wxcharts_wxdoughnutchartctrl.o: src/wxdoughnutchartctrl.cpp
	$(CXX) -c -o $@ $(CPPFLAGS) $(CXXFLAGS) -MD -MP -fPIC -DPIC -pthread -Iinclude/wx/charts `wx-config --cxxflags --libs` src/wxdoughnutchartctrl.cpp

$(_builddir)wxcharts_wxohlcchartoptions.o: src/wxohlcchartoptions.cpp
	$(CXX) -c -o $@ $(CPPFLAGS) $(CXXFLAGS) -MD -MP -fPIC -DPIC -pthread -Iinclude/wx/charts `wx-config --cxxflags --libs` src/wxohlcchartoptions.cpp

$(_builddir)wxcharts_wxohlcchartctrl.o: src/wxohlcchartctrl.cpp
	$(CXX) -c -o $@ $(CPPFLAGS) $(CXXFLAGS) -MD -MP -fPIC -DPIC -pthread -Iinclude/wx/charts `wx-config --cxxflags --libs` src/wxohlcchartctrl.cpp

$(_builddir)wxcharts_wxpiechartoptions.o: src/wxpiechartoptions.cpp
	$(CXX) -c -o $@ $(CPPFLAGS) $(CXXFLAGS) -MD -MP -fPIC -DPIC -pthread -Iinclude/wx/charts `wx-config --cxxflags --libs` src/wxpiechartoptions.cpp

$(_builddir)wxcharts_wxpiechartctrl.o: src/wxpiechartctrl.cpp
	$(CXX) -c -o $@ $(CPPFLAGS) $(CXXFLAGS) -MD -MP -fPIC -DPIC -pthread -Iinclude/wx/charts `wx-config --cxxflags --libs` src/wxpiechartctrl.cpp

$(_builddir)wxcharts_wxpolarareachartoptions.o: src/wxpolarareachartoptions.cpp
	$(CXX) -c -o $@ $(CPPFLAGS) $(CXXFLAGS) -MD -MP -fPIC -DPIC -pthread -Iinclude/wx/charts `wx-config --cxxflags --libs` src/wxpolarareachartoptions.cpp

$(_builddir)wxcharts_wxpolarareachartctrl.o: src/wxpolarareachartctrl.cpp
	$(CXX) -c -o $@ $(CPPFLAGS) $(CXXFLAGS) -MD -MP -fPIC -DPIC -pthread -Iinclude/wx/charts `wx-config --cxxflags --libs` src/wxpolarareachartctrl.cpp

$(_builddir)wxcharts_wxradarchartoptions.o: src/wxradarchartoptions.cpp
	$(CXX) -c -o $@ $(CPPFLAGS) $(CXXFLAGS) -MD -MP -fPIC -DPIC -pthread -Iinclude/wx/charts `wx-config --cxxflags --libs` src/wxradarchartoptions.cpp

$(_builddir)wxcharts_wxradarchartctrl.o: src/wxradarchartctrl.cpp
	$(CXX) -c -o $@ $(CPPFLAGS) $(CXXFLAGS) -MD -MP -fPIC -DPIC -pthread -Iinclude/wx/charts `wx-config --cxxflags --libs` src/wxradarchartctrl.cpp

$(_builddir)wxcharts_wxscatterplotoptions.o: src/wxscatterplotoptions.cpp
	$(CXX) -c -o $@ $(CPPFLAGS) $(CXXFLAGS) -MD -MP -fPIC -DPIC -pthread -Iinclude/wx/charts `wx-config --cxxflags --libs` src/wxscatterplotoptions.cpp

$(_builddir)wxcharts_wxscatterplotctrl.o: src/wxscatterplotctrl.cpp
	$(CXX) -c -o $@ $(CPPFLAGS) $(CXXFLAGS) -MD -MP -fPIC -DPIC -pthread -Iinclude/wx/charts `wx-config --cxxflags --libs` src/wxscatterplotctrl.cpp

$(_builddir)wxcharts_wxbubblechartoptions.o: src/wxbubblechartoptions.cpp
	$(CXX) -c -o $@ $(CPPFLAGS) $(CXXFLAGS) -MD -MP -fPIC -DPIC -pthread -Iinclude/wx/charts `wx-config --cxxflags --libs` src/wxbubblechartoptions.cpp

$(_builddir)wxcharts_wxbubblechartctrl.o: src/wxbubblechartctrl.cpp
	$(CXX) -c -o $@ $(CPPFLAGS) $(CXXFLAGS) -MD -MP -fPIC -DPIC -pthread -Iinclude/wx/charts `wx-config --cxxflags --libs` src/wxbubblechartctrl.cpp

clean:
	rm -f $(_builddir)*.o
	rm -f $(_builddir)*.d
	rm -f $(_builddir)build/bakefiles/../../lib$(if $(call _equal,$(config),Debug),wxchartsd,wxcharts).a

.PHONY: all clean

# Dependencies tracking:
-include $(_builddir)*.d
