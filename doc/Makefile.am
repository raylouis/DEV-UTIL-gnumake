# -*-Makefile-*-, or close enough

TEXI2HTML = texi2html
TEXI2HTML_FLAGS = -split_chapter

info_TEXINFOS =	make.texi
make_TEXINFOS = fdl.texi make-stds.texi

CLEANFILES = make*.html

## ----------------------------- ##
## Other documentation formats.  ##
## ----------------------------- ##

html: make_1.html

make_1.html: $(info_TEXINFOS) $(make_TEXINFOS)
	$(TEXI2HTML) $(TEXI2HTML_FLAGS) $(srcdir)/make.texi

.PHONY: html
