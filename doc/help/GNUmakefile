IVDEPTH = ../..
include $(IVDEPTH)/make/ivcommondefs

all:

install:
	mkdir -p $(IVHELPDIR)/Inventor
	for h in *.help.pdf; do $(INSTALL) -m 644 $$h $(IVHELPDIR)/Inventor; done

include $(IVCOMMONRULES)
