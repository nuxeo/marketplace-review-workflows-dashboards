# Nuxeo Review Workflows Dashboards

## About

This project allows building the Marketplace package for the
[Review Workflows Dashboards](https://github.com/nuxeo/nuxeo-review-workflows-dashboards) addon.

## Building

To build and run the tests, simply start the Maven build:

    mvn clean install

To run functional tests:

    mvn clean install -Pftest

## Installing

To install the package:

 1. Take a fresh Nuxeo CAP (>= 7.4).

 2. Install the nuxeo-review-workflows-dashboards package:
      - From the AdminCenter (Upload + install)
      - From the command line using `nuxeoctl mp-install package.zip`
