themedir = $(datadir)/icons/Adwaita-Ubuntu/output/Adwaita-Ubuntu
theme_DATA =   
EXTRA_DIST = $(theme_DATA)
install-data-local: install-themeDATA
	(cd "$(DESTDIR)$(themedir)" && $(ICONMAP) -c Adwaita-Ubuntu )
MAINTAINERCLEANFILES = Makefile.in
