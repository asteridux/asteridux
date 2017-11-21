# Asteridux

Build status: [![CircleCI](https://circleci.com/gh/asteridux/asteridux.svg?style=svg)](https://circleci.com/gh/AntJanus/asteridux:Why)

## What?

Asteridux is a minimalist boilerplate for JavaScript projects. It includes a testing suite, a bundler, and a Babel setup.

## Why?

I've built enough libraries to know that the longest and most annoying part of creating a library is the setup. Asteridux gets rid of the tediousness of including all the right documentation, all the right linting setups, and setting up transpilers/bundlers. 

## Requirements

## Installation and setup

Clone the repo:

```
git clone ssh:git@github.com:asteridux/asteridux.git
```

Delete all information pertaining to Asteridux:

1. package.json author/name fields
2. README.md contents

And pick a bundler.

### Which bundler to choose

In the simplest terms, if you're building an app, use Webpack. If you're building a library or a CLI, use Rollup.
