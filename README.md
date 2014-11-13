
## Latest version of nvd3 can be found here as the original project was abandoned.

Sadly the original developer of nvd3 has long since moved on to other things, and the
last maintainer said he does not have time anymore.  Thanks to both of them for all the
great work put into the project thus far, and with the magic of open source licensing
we can keep on improving it!

Latest version is 1.5.16 ( [view](https://github.com/liquidpele/nvd3/tree/1.5.16/build) | [zip](https://github.com/liquidpele/nvd3/zipball/1.5.16) | [tar.gz](https://github.com/liquidpele/nvd3/tarball/1.5.16) )

## Overview
A reusable chart library for d3.js

You can also check out the [examples page](http://nvd3.org/ghpages/examples.html).
**Note:** The examples on nvd3.org may be outdated and the download button there links to the outdated repo.

For examples on how to use the latest NVD3, please checkout the **examples/** directory in the repository.

---

# Current development focus

- Clean things up
- Merge in pull requests and bugfixes

---

If one of [the existing models](https://github.com/liquidpele/nvd3/tree/development/src/models)
doesn't meet your needs, fork the project, implement the model and an example using it,
send us a pull request, for consideration for inclusion in the project.

We cannot honor all pull requests, but we will review all of them.

Please do not aggregate pull requests. Aggregated pull requests are actually more difficult to review.

We are currently changing our branch structure so that master will be gauranteed stable. In addition,
there is now a "development" branch. This branch reflects the latest changes to NVD3 and is not necessarily stable.

---

## Building latest

1. First check out the testing branch, e.g.:  git clone https://github.com/liquidpele/nvd3.git
2. make sure nodejs is installed via your system's package manager.
3. have node download it's required modules with:  npm install
4. build with:  grunt production

You should now have a "build" directory with the js and css files within.

## Supported Browsers
NVD3 runs best on WebKit based browsers.

* Google Chrome: latest version
* Opera 15+ (i.e. webkit version)
* Safari: latest version
* Firefox: latest version
* Internet Explorer: 10+
