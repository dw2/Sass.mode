# Sass.mode

Panic says that “Coda 2 ships with Sass support out-of-box”. Bullshit. It ships with SCSS support, CSS-like fallback of Sass. Originally Sass have indented syntax, like Stylus. And this Coda Mode makes possible to white Sass stylesheets with comfort (as we can provide it).

### Compatibility

+ **[Coda 2](http://www.panic.com/coda/)**

### Supported Extensions

+ .sass with indented syntax

### Installation

You can do it via terminal if you think that you're in 80's

	cd ~/Library/Application\ Support/Coda/Modes
	git clone git://github.com/Grawl/Sass.mode.git Sass.mode

Or you can do it like we do it in our shiny future:

+ [download zipball](master.zip) of this repository
+ unzip and remove “-master” from folder name so it transforms into Coda Mode, because file name will be `Sass.mode`
+ open it with double click or ⌘↓ and Coda will move it into `~/Library/Application Support/Coda/Modes` and relaunch itself

Also you can move `Sass.mode` to `Applications/Coda 2/Contents/Rescourses` if you have troubles with your Library or something other.

### ToDo

+ Variables autocomplete
+ Mixins autocomplete
+ Grouping values with parameters in autocomplete like Coda [does it with colors](http://d.pr/i/Ctdu) in CSS mode.

### Credit for the source repos

+ [Author: Tom-Marius Olsen](http://upstruct.svn.beanstalkapp.com/sass/)
+ [@Brajeshwar/Sass.mode](http://github.com/Brajeshwar/Sass.mode) — SCSS mode
+ [@ry5n/ry5n-sass.mode](https://github.com/ry5n/ry5n-sass.mode) — Sass mode
+ [@dw2/Sass.mode](https://github.com/dw2/Sass.mode) – Coda 2 support for Coda mode
+ [@grawl/Sass.mode](https://github.com/Grawl/Sass.mode) – Autocomplete fixes

### References

[More about Mode Customization](http://www.codingmonkeys.de/subethaedit/mode.html)
