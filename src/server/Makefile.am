bin_PROGRAMS = pokerServer
pokerServer_SOURCES = main.c
pokerServer_SOURCES += ../global.h
pokerServer_SOURCES += server_network.c server_network.h
pokerServer_SOURCES += events.c events.h logic.c logic.h 
pokerServer_SOURCES += gameServer/gameLogic.c gameServer/gameLogic.h
pokerServer_SOURCES += gameServer/win.c gameServer/win.h
pokerServer_SOURCES += gameServer/shared.c gameServer/shared.h
pokerServer_SOURCES += gameServer/start.c gameServer/start.h
noinst_LIBRARIES = libtestcorelogic.a
libtestcorelogic_a_SOURCES = gameServer/shared.c gameServer/shared.h
libtestcorelogic_a_SOURCES += gameServer/win.c gameServer/win.h
AM_CFLAGS = -Wall -I$(top_builddir)/src -I$(top_builddir)/src/server -I$(top_builddir)/src/server/lobbiServer -I$(top_builddir)/src/server/gameServer
AM_CFLAGS += -Wunused-function #static functions in modules warning
