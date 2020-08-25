surf - simple webkit-based browser
==================================
surf is a simple Web browser based on WebKit/GTK+.

Requirements
------------
In order to build surf you need GTK+ and Webkit/GTK+ header files.

In order to use the functionality of the url-bar, also install [dmenu](https://tools.suckless.org/dmenu)

Installation
------------
As root, run:

    `make clean install`

Running surf
------------
run
	`surf [URI]`

See the manpage for further options.

Running surf in tabbed
----------------------
For running surf in [tabbed](https://tools.suckless.org/tabbed) there is a script included in the distribution, which is run like this:

	`surf-open.sh [URI]`

Further invocations of the script will run surf with the specified URI in this
instance of tabbed.


oqolarte's surf build includes the ff patches:
- home page
- web search
