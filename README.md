Energia MSP430 Makefile
-----------------------

I'm the kind of programmer that hates complicated IDEs, moreover I can't suffer Java(TM), for this reason I tend to use Makefiles to compile MCU code, this is what I've been doing with Arduino during the last years.

Yesterday I received this new Launchpad board and the very first thing I've done was to write a Makefile to compile and upload programs to the board.

This Makefile is freely adapted from the good job done by Tim Marston at http://ed.am/dev/make/arduino-mk

This Makefile is far from being complete and I'm fighting with a strange issue (help welcome!): it is necessary to explicitly include main.cpp (even if it's already included in the (ar)chived lib arduino.a. My understanding of gcc compilation steps is too basic to fix this issue, but the Makefile is working fine.


