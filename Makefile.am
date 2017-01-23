# Main Makefile for DOSBox

EXTRA_DIST = autogen.sh
SUBDIRS = src include docs visualc_net

fix: src/dosbox.js
	sed -i bak '/!dest ||  \/\/ connection-less sockets are always ready to read/s/^/\/\//g' src/dosbox.js
