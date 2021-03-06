## 2015-04-03 - Release 0.10.0

- Add Debian 8 support
- Add acceptance tests for debian6 and centos6 to travis matrix
- Remove RedHat 5 support (may still work but untested)

## 2015-03-24 - Release 0.9.0

- Support Debian Jessie (with tomcat7)
- Add acceptance tests on Travis CI

## 2015-03-24 - Release 0.8.10

- Update Gemfile

## 2015-03-13 - Release 0.8.9

- Fix a bug with systemd service file

## 2015-03-11 - Release 0.8.8

- Fix: Tomcat::Connector should refresh Service

## 2015-02-19 - Release 0.8.7

- Fix for future parser

## 2015-02-18 - Release 0.8.6

- Revert fix

## 2015-02-18 - Release 0.8.5

- Fix future parser issue

## 2015-01-29 - Release 0.8.4

- Don't use fakeroot for unit tests
- Fix future parser issues
- Use absolute names in class inclusions
- Use undef instead of empty strings

## 2015-01-07 - Release 0.8.3

- Fix unquoted strings in cases

## 2015-01-05 - Release 0.8.2

- Add CHANGELOG.md
- Fix license name in metadata.json
- Simplify bundler cache in Travis CI
