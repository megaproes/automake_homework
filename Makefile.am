SUBDIRS = include src
EXTRA_DIST = README.md

.PHONY: clean-all
clean-all: uninstall maintainer-clean
	@echo "Removing all Autotools-generated files..."
	@rm -rf autom4te.cache aclocal.m4 configure config.* Makefile.in depcomp install-sh missing compile
	@find . -name '.deps' -o -name '.libs' -o -name '*.o' -delete
	@echo "Full cleanup complete."
