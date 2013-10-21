## Employee Directory ##

### Sample Application built with Backbone.js and TopCoat ###

"Backbone Directory" is a simple Employee Directory application built with [Backbone.js](http://backbonejs.org) and [Topcoat](http://topcoat.io).

Refer to [this blog post](http://coenraets.org) for more information about the application.

The application runs out-of-the-box with an in-memory data store.
You will however have to serve it through a local webserver, as you might experience [CORS](http://www.html5rocks.com/en/tutorials/cors/) issues when opening index.html through the file:// pseudo-protocol in your browser.

On a Mac you can run ./runlocal which starts a simple python-based http server and opens http://0.0.0.0:8000 in your default browser.
