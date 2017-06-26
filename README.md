# Ionic Travis

master branch: [![Build Status](https://travis-ci.org/okode/ionic-travis.svg?branch=master)](https://travis-ci.org/okode/ionic-travis)

develop branch: [![Build Status](https://travis-ci.org/okode/ionic-travis.svg?branch=develop)](https://travis-ci.org/okode/ionic-travis)

Ionic app built with Travis CI.

Supported platforms:

* iOS
* Android

## Building iOS platform

```
$ yarn install
$ cordova platform add ios --nofetch
$ ionic cordova build ios --prod --release
```

## Building Android platform

```
$ yarn install
$ cordova platform add android --nofetch
$ ionic cordova build android --prod --release
```

