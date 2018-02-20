themedir = $(datadir)/icons/Adwaita-Ubuntu/Adwaita/64x64
theme_DATA =   
EXTRA_DIST = $(theme_DATA)
install-data-local: install-themeDATA
	(cd "$(DESTDIR)$(themedir)" && $(ICONMAP) -c 64x64 )
MAINTAINERCLEANFILES = Makefile.in
