Web servers
=

A web server refers to either the hardware (computer) or software (application) that helps deliver web content.

[Apache](http://httpd.apache.org/)

* [apachectl](http://httpd.apache.org/docs/2.2/programs/apachectl.html) a command line tool for controlling Apache.
* [a2enmod/a2dismod](http://man.he.net/man8/a2enmod) a command line tool for enabling and disabling Apache2 modules.

## Caching / Optimizing

A web server is responsible for and should be configured to set HTTP cache headers (see [HTTP > Caching](http.md#caching)) appropriately.

## Web Accelerators

A web accelerator serves as a front for your web server, speeding up delivery by various techniques including full-page caching and gzipping responses. [Varnish](https://www.varnish-cache.org/) is a popular, open source example.