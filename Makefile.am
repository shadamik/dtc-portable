ACLOCAL_AMFLAGS = -I m4

SUBDIRS = lib

all-local:
	cd dtc && $(MAKE) -f $(abs_top_srcdir)/Makefile.wrapper $(AM_MAKEFLAGS) version_gen.h all
check-local:
	cd dtc && $(MAKE) -f $(abs_top_srcdir)/Makefile.wrapper $(AM_MAKEFLAGS) check
clean-local:
	cd dtc && $(MAKE) -f $(abs_top_srcdir)/Makefile.wrapper $(AM_MAKEFLAGS) clean

install-data-local:
	cd dtc && $(MAKE) -f $(abs_top_srcdir)/Makefile.wrapper $(AM_MAKEFLAGS) install-includes
install-exec-local:
	cd dtc && $(MAKE) -f $(abs_top_srcdir)/Makefile.wrapper $(AM_MAKEFLAGS) install-bin install-lib
