Changelog
---------

0.4.0 (unreleased)
++++++++++++++++++

Features:

* Add `resource_class_args` and `resource_class_kwargs` to `FlaskApiSpec.register` for passing constructor arguments to `MethodResource` classes. Thanks @elatomo.
* Add `FlaskApiSpec.init_app` method to support app factories (#21). Thanks @lafrech for the suggestion and thanks @dases for the PR.
* Defer registering views until `init_app` is called. Thanks @kageurufu for the PR.
* Add support for documenting headers and query params (#32). Thanks @rodjjo.

Other changes:

- Test against Python 3.6. Drop support for Python 3.3.
- Support apispec>=0.17.0. Thanks @rth for fixing support for 0.20.0.

0.3.2 (2015-12-06)
++++++++++++++++++

* Fix Swagger-UI favicons. Thanks @benbeadle.

0.3.1 (2015-11-12)
++++++++++++++++++

* Update Swagger-UI assets. Thanks @evocateur.

0.3.0 (2015-11-11)
++++++++++++++++++

* Bundle templates and static files with install. Thanks @bmorgan21.
* Use readthedocs for documentation.

0.2.0 (2015-11-03)
++++++++++++++++++

* Add `FlaskApiSpec` Flask extension.
* Serve Swagger and Swagger-UI automatically.
* Reorganize file structure.

0.1.3 (2015-11-01)
++++++++++++++++++

* Rename to flask-apispec.
* Update to latest version of apispec.

0.1.2
++++++++++++++++++

* Update to latest version of webargs.

0.1.1
++++++++++++++++++

* Restrict inheritance to HTTP verbs.

0.1.0
++++++++++++++++++

* First release.
