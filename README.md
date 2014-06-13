pygpiod - (c) 2014-06-12 Leif Sawyer

loosely based on a script by Alex Eames http://RasPi.tv


This is a simple daemon-esque script that is meant to be run in the background
at startup on a Raspberry Pi.

It allows for triggering of different types of events (short-press, long-press, longer-press)
in order to provide the maximum amount of functionality with the limited number of GPIO lanes.

This initial push is simply how I use it on my system.

It should/could be re-written to be slightly more modular and easier to configure,
but I'm old, fat, and lazy, and can't hardly be arsed to fix typos, let alone a
complete rewrite.

But if you like it and want to use it, have fun, and I'll accept patches for additional/better
functionality, because otherwise what is the point of having it on GitHub?

