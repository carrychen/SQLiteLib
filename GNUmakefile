#
# GNUmakefile - Generated by ProjectCenter
#
ifeq ($(GNUSTEP_MAKEFILES),)
 GNUSTEP_MAKEFILES := $(shell gnustep-config --variable=GNUSTEP_MAKEFILES 2>/dev/null)
endif
ifeq ($(GNUSTEP_MAKEFILES),)
 $(error You need to set GNUSTEP_MAKEFILES before compiling!)
endif
include $(GNUSTEP_MAKEFILES)/common.make

#
# Library
#
VERSION = 0.1
PACKAGE_NAME = SQLiteLib
LIBRARY_VAR = PACKAGE_NAME
LIBRARY_NAME = lib$(PACKAGE_NAME)
libSQLiteLib_HEADER_FILES_DIR = .
libSQLiteLib_HEADER_FILES_INSTALL_DIR = /$(PACKAGE_NAME)


#
# Resource files
#
$(LIBRARY_NAME)_RESOURCE_FILES =  


#
# Public headers (will be installed)
#
$(LIBRARY_NAME)_HEADER_FILES = \
lib$(PACKAGE_NAME).h  
#
# Class files
#
$(LIBRARY_NAME)_OBJC_FILES = \
lib$(PACKAGE_NAME).m  \
src/SQLDatabase.m \
src/SQLResult.m \
src/SQLRow.m



#
# Makefiles
#
-include GNUmakefile.preamble
include $(GNUSTEP_MAKEFILES)/aggregate.make
include $(GNUSTEP_MAKEFILES)/library.make
-include GNUmakefile.postamble
