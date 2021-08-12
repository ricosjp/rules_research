SUBDIRS := $(wildcard */)

.PHONY: all
all:
	for dir in $(SUBDIRS); do \
      make -C $$dir all; \
  done
