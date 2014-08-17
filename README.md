# teleprompter

[![Build Status](https://secure.travis-ci.org/michaeljoseph/teleprompter.png)](http://travis-ci.org/michaeljoseph/teleprompter)
[![Stories in Ready](https://badge.waffle.io/michaeljoseph/teleprompter.png?label=ready)](https://waffle.io/michaeljoseph/teleprompter) [![pypi version](https://badge.fury.io/py/teleprompter.png)](http://badge.fury.io/py/teleprompter)
[![# of downloads](https://pypip.in/d/teleprompter/badge.png)](https://crate.io/packages/teleprompter?version=latest)
[![code coverage](https://coveralls.io/repos/michaeljoseph/teleprompter/badge.png?branch=master)](https://coveralls.io/r/michaeljoseph/teleprompter?branch=master)

## Overview

Helping humans help robots prompt humans for information

* features
* and stuff 

## Usage

Install `teleprompter`:

    pip install teleprompter

Then execute the sample cli:

   teleprompter

## Documentation

[API Documentation](http://teleprompter.rtfd.org)

## Testing

Install development requirements:

    pip install -r requirements.txt

Tests can then be run with:

    nosetests

Lint the project with:

    flake8 teleprompter tests

## API documentation

Generate the documentation with:

    cd docs && PYTHONPATH=.. make singlehtml

To monitor changes to Python files and execute flake8 and nosetests
automatically, execute the following from the root project directory:

    stir