all:
	dot -Tpng -O dog.dot
	smu < index.tpl > index.html
	sent -p slides/q1 -r 1024x768 index.sent
	@echo Done!

.PHONY: all
