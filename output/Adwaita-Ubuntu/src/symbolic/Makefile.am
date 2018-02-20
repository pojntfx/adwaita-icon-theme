themedir = $(datadir)/icons/Adwaita-Ubuntu/src/symbolic
theme_DATA = gnome-stencils.svg  
EXTRA_DIST = $(theme_DATA)
install-data-local: install-themeDATA
	(cd "$(DESTDIR)$(themedir)" && $(ICONMAP) -c symbolic )
MAINTAINERCLEANFILES = Makefile.in
