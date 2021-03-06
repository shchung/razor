## 0.4.0 / 2013-03-01

### New features

* Add support for Postgres persistence plugin. ([@fnichol][])
* Add support for Ubuntu 12.10. ([@sbates][])

### Improvements

* Update razor/app/git_rev attribute to '0.9.0' tag. ([@fnichol][])
* Convert cookbook testing from Jamie to Test Kitchen (1.0 alpha).
  ([@fnichol][])


## 0.3.2 / 2012-12-27

* Sync version in Changelog/metadata.rb/Git tag. ([@fnichol][])


## 0.3.0 / 2012-12-27

## Bug fixes

* Add postgresql cookbook for new Gemfile dependency (pg gem). ([@fnichol][])

### Improvements

* Updates to README. ([@fnichol][])
* Use an underscore in recipe names that are composed in razor::default.
  ([@fnichol][])
* [FC044]: Avoid bare attribute keys. ([@fnichol][])


## 0.2.2 / 2012-11-15

## Bug fixes

* Ensure tftp files are group/world readable. ([@fnichol][])


## 0.2.0 / 2012-11-07

### Attribute default updates

* razor/app/git\_rev now defaults to `"master"` (previously `"0.7.0"`).
  ([@fnichol][])

### Improvements

* Add foodcritic testing and make TravisCI ready. ([@fnichol][])
* Run bundler with `--without test` to exclude testing dependencies.
  ([@fnichol][])


## 0.1.0 / 2012-09-04

The initial release.

[@fnichol]: https://github.com/fnichol
[@sbates]: https://github.com/sbates
