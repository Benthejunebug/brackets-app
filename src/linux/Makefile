
build:
	valac -v --vapidir vala \
		--pkg gtk+-2.0 \
		--pkg gio-2.0 \
		--pkg webkit-1.0 \
		--pkg javascriptcore \
		-o ../../bin/linux/brackets \
		main.vala frame.vala browser.vala bracketswindow.vala

compile:
	valac -v --vapidir vala \
		--pkg gtk+-2.0 \
		--pkg gio-2.0 \
		--pkg webkit-1.0 \
		--pkg javascriptcore \
		-o ../../bin/linux/brackets \
		-C main.vala frame.vala browser.vala bracketswindow.vala

run:
	../../bin/linux/brackets
