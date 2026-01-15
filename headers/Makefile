VERSION = 6
PATCHLEVEL = 1
SUBLEVEL = 115

# Standard clean/install targets for Android Build System
headers_install:
	@echo "  INSTALL headers to $(O)/usr"
	@mkdir -p $(O)/usr
	@rsync -mrq --exclude=Makefile $(shell pwd)/ $(O)/

modules_install:
	@true

all:
	@true
