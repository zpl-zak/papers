all:
	dot -Tpng -O dog.dot
	smu < index.tpl > index.html
	sent -p slides/q1 index.sent
	@echo Done!

.PHONY: all
