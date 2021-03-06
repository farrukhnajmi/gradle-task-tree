Changelog
=========

This changelog format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/).  
This project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

Unreleased
----------------------------
Display finalizer tasks (i.e. those declared with`finalizedBy`)

Version 1.3.1 (2018-10-08)
----------------------------

* Compatibility with gradle version 5.0-milestone-1

Version 1.3 (2017-03-04)
----------------------------

* Compatibility with all gradle versions >= 2.3
* Update gradle wrapper to 3.4
* Better multi-project handling:
   - Applying the plugin on the root project adds the taskTree task to all child projects.
   - Applying the plugin under `allrojects`  or `subprojects` exhibits the same behavior (and does not fail anymore due to `task taskTree is already defined`)

