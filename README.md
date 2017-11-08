Facebook Proxy
==============

> A proxy server to unleash the Facebook Graph API.

[![Build Status](https://img.shields.io/travis/redaxmedia/facebook-proxy.svg)](https://travis-ci.org/redaxmedia/facebook-proxy)
[![Dependency Status](https://gemnasium.com/badges/github.com/redaxmedia/facebook-proxy.svg)](https://gemnasium.com/github.com/redaxmedia/facebook-proxy)
[![NPM Version](https://img.shields.io/npm/v/facebook-proxy.svg)](https://www.npmjs.com/package/facebook-proxy)
[![GitHub Stats](https://img.shields.io/badge/github-stats-ff5500.svg)](http://githubstats.com/redaxmedia/facebook-proxy)


Installation
------------

```
npm install facebook-proxy
```


Setup
-----

Create a `.env` file to define your environment variables:

```
FACEBOOK_CLIENT_ID=169734130242059
FACEBOOK_CLIENT_SECRET=f133d7f3a851c30400c35a6fa11273f8
FACEBOOK_GRANT_TYPE=client_credentials
SERVER_HOST=localhost
SERVER_PORT=3000
```


Usage
-----

```
bin/facebook-proxy
```
