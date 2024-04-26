default: help

help:
	@echo "Please choose one of the following targets:"
	@echo "  - amd"
	@echo "  - nvidia"
	@echo "  - intel"
	@echo "  - oneapi"

.PHONY: amd nvidia intel
amd:
	make -C amd/ image
nvidia:
	make -C nvidia/ dtk image
intel:
	make -C intel/ image
oneapi:
	make -C oneapi/ image
