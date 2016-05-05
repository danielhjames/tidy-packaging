# tidy-packaging
Debian/Ubuntu packaging for HTML Tidy https://github.com/htacg

The tidy packages in Debian/Ubuntu are very out of date. This packaging is an update for current Debian standards and the latest upstream release, 5.2.0.

Notes

1. Source package was renamed to prevent it being built as tidy-html5 and to use datestamp versions as in Debian/Ubuntu

2. The man page was copied into the packaging from upstream as a static file. Building it from the sources each time seems like unwanted overhead.

3. There do not seem to be any extra docs in the sources that I could find, so I deprecated the tidy-doc package for now.

Feedback welcome!
