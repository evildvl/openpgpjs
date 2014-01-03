OpenPGP.js [![Build Status](https://secure.travis-ci.org/openpgpjs/openpgpjs.png?branch=master,v0.1.x)](http://travis-ci.org/openpgpjs/openpgpjs)
==========

[OpenPGP.js](http://openpgpjs.org/) is a Javascript implementation of the OpenPGP protocol. This is defined in [RFC 4880](http://tools.ietf.org/html/rfc4880).

# How do I use it?
To build the library, download a tagged version from [releases](https://github.com/openpgpjs/openpgpjs/releases) and the build the library like so:

    npm install && grunt

Then take the use the minified file from `resources/openpgp.min.js` and use it in your project.

# I need some help
## Mailing List
You can [sign up](http://list.openpgpjs.org/) for our mailing list and ask for help there.  We've recently worked on getting our [archive up and running](http://www.mail-archive.com/list@openpgpjs.org/).

## Documentation
A jsdoc build of our code comments is available at [doc/index.html](doc/index.html). Public calls should generally be made through the OpenPGP object [doc/openpgp.html](doc/openpgp.html).

# How do I get involved?
You want to help, great! Go ahead and fork our repo, make your changes
and make a pull request.

It is extra awesome if you write tests for the code you change. Our test coverage is relatively weak, so if you can add cases that is great.

# What License do you use?
GNU Lesser General Public License (2.1). Please take a look at the [LICENSE](LICENSE) file for more information.

# What are the requirements to use it?
OpenPGP.js currently only fully supports Chrome. Firefox support should be coming soon with the advent of Firefox 23 with native javascript support for `window.crypto.getRandomValues`. If you can help us support more browsers and situations, please chip in!

# Resources
Below is a collection of resources, many of these were projects that were in someway a precursor to the current OpenPGP.js project. If you'd like to add your link here, please do so in a pull request or email to the list.

* [http://www.hanewin.net/encrypt/](http://www.hanewin.net/encrypt/)
* [https://github.com/seancolyer/gmail-crypt](https://github.com/seancolyer/gmail-crypt)
* [https://github.com/mete0r/openpgp-js](https://github.com/mete0r/openpgp-js)
* [http://fitblip.github.com/JSPGP-Stuffs/](http://fitblip.github.com/JSPGP-Stuffs/)
* [http://qooxdoo.org/contrib/project/crypto](http://qooxdoo.org/contrib/project/crypto)
* [https://github.com/GPGTools/Mobile/wiki/Introduction](https://github.com/GPGTools/Mobile/wiki/Introduction)
* [http://gpg4browsers.recurity.com/](http://gpg4browsers.recurity.com/)
