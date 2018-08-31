<p align="center"><img width=250 src="https://s3-us-west-2.amazonaws.com/scalabel-public/www/logo/scalable_dark.svg" /></p>

--------------------------------------------------------------------------------


[![Build Status](https://travis-ci.com/ucbdrive/scalabel.svg?token=9QKS6inVmkjyhrWUHjqT&branch=master)](https://travis-ci.com/ucbdrive/scalabel)
[![Language grade: JavaScript](https://img.shields.io/lgtm/grade/javascript/g/ucbdrive/scalabel.svg)](https://lgtm.com/projects/g/ucbdrive/scalabel/context:javascript)
[![Language grade: Python](https://img.shields.io/lgtm/grade/python/g/ucbdrive/scalabel.svg)](https://lgtm.com/projects/g/ucbdrive/scalabel/context:python) 

Scalabel (pronounced "scalable") is a versatile and scalable tool that supports all kinds of annotations needed in a driving database. It supports bounding box, semantic instance segmentation, and video tracking.

![scalabel interface](https://s3-us-west-2.amazonaws.com/www.scalabel.ai/images/scalabel_teaser_interface.jpg)

# Usage and Demo

Please check the [documentation](http://www.scalabel.ai/doc) for detailed usage instructions.

## Installation (MacOS/Darwin)

Install Homebrew; set `https://brew.sh/`
Install Node.js: `brew install node`
Install Node.js components: `npm install`
Compile Node.js software: `npx webpack --config webpack.config.js --mode=production`
Install Go Language (e.g. `brew install go`)
Set environment variable GOPATH: `setenv GOPATH ~/go`
Build software using Go: `go build -i -o $GOPATH/bin/scalabel ./server/go`
Run server: `$GOPATH/bin/scalabel --config app/config/default_config.yml`

