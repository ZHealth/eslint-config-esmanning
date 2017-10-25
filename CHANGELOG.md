# eslint-config-esmanning change log

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/)
and this project adheres to [Semantic Versioning](http://semver.org/).

## 2.0.0

- chore: banish lock file
- chore(pkg): move eslint to dev deps
- docs: update install instructions

BREAKING CHANGE: eslint is no longer a direct dependency

after npm@5 it's necessary to install eslint as a direct dependency
in projects using this config, as the eslint command is not made
available otherwise

## 1.0.4

- deps: semver patch only for eslint

## 1.0.3

- deps: update eslint to ^3.9.0 (#6)
- deps: update eslint-plugin-react to ~6.5.0 (#7)

## 1.0.2

- deps: semver patches only (#4)

## 1.0.1

- deps: eslint-plugin-promise@^3.3.0 (#1)

## 1.0.0

- stable release

## 0.0.0

- alpha release (you better not use this)
