#########
Changelog
#########
All notable changes to the Storehouse NApp  project will be documented in this
file.

[UNRELEASED] - Under development
********************************
Changed
=======
- Continuous integration enabled at scrutinizer.


[1.3.0] - 2019-12-13
********************
Added
=====
- Added new `etcd` backend (experimental).
- Added abstract base class for all backend classes.
- Added setup script.
- Added a new id parameter to Box class.
- Added future deprecation warning to `name` parameter.

Changed
=======
- Return original exception objects on event errors.

Fixed
=====
- Fixed looping issue when trying to update a nonexistent box.


[1.2.0] - 2019-08-30
********************
Added
=====
- Added boxes and namespaces backup methods to the FileSystem backend,
  with the respective REST API endpoints.


[1.1.0] - 2018-06-15
********************
Added
=====
- Added Event-based methods.
- Added RESTful API.
- Added support for creating, listing, retrieving and deleting data using the
  local filesystem.
- Added endpoint to search by some attribute in the box metadata.
- Added methods to save a metadata in cache.
- Added name attribute in Box class.
- Added methods to update a box from namespace.

Fixed
=====
- Fix docstrings.

[1.0.0] - 2018-04-20
********************************
Added
=====
- Add documentation for the NApp.
- Add try/except statement to event methods.
- Add methods to listen to storage events.
- Add docstrings to all files.
