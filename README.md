Mirrorboard Colemak
===================

An xkb file for a version of Colemak that allows for everything to be typed with just the left hand.

Based on [Mirrorboard](http://blog.xkcd.com/2007/08/14/mirrorboard-a-one-handed-keyboard-layout-for-the-lazy/).

Usage
-----

	xkbcomp mirrorboard.xkb $DISPLAY

Leaves the keyboard untouched for normal typing.

Normally:

	1 2 3 4 5 6 7
	q w f p g j l
	a r s t d h n
	- z x c v b

With alt held down:

	0 9 8 7 6 - =
	; y u l j [ ]
	o i e n h ' \
	/ . , m k b

Alt-shift:

	( ) * & ^ _ +
	: Y U L J { }
	O I E N H " |
	? > < M K B
