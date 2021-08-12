SUBDIRS := $(wildcard */)
.PHONY: $(SUBDIRS)

%::
	$(MAKE) $(SUBDIRS) MAKECMDGOALS=$@

$(SUBDIRS):
	make -C $@ $(MAKECMDGOALS)
