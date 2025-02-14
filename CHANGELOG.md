# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [0.2.0](https://github.com/fabiocaccamo/django-extra-settings/releases/tag/0.2.0) - 2022-01-18
-   Added `description` to setting model. #16 - Credits: [@obdulia-losantos](https://github.com/obdulia-losantos)
-   Added `EXTRA_SETTINGS_ENFORCE_UPPERCASE_SETTINGS` setting (default `True`).
-   Added `EXTRA_SETTINGS_SHOW_TYPE_LIST_FILTER` setting (default `False`).
-   Fixed missing comma in tests settings `MIDDLEWARE_CLASSES`. #14

## [0.1.4](https://github.com/fabiocaccamo/django-extra-settings/releases/tag/0.1.4) - 2021-12-08
-   Added `python 3.10` support.
-   Added `django 4.0` support.
-   Fixed tests settings warnings.
-   Fixed setup warning.

## [0.1.3](https://github.com/fabiocaccamo/django-extra-settings/releases/tag/0.1.3) - 2021-10-08
-   Changed `upload_to` to callable. #11 - thanks to @thlnndrs
-   Fixed `setup.py` unicode error.
-   Added `python 3.9` and `django 3.2` to `tox` and `travis`.

## [0.1.2](https://github.com/fabiocaccamo/django-extra-settings/releases/tag/0.1.2) - 2020-09-04
-   Added `models.DurationField` support.

## [0.1.1](https://github.com/fabiocaccamo/django-extra-settings/releases/tag/0.1.1) - 2020-02-13
-   Fixed `django 1.8` compatibility.
-   Improved code quality.

## [0.1.0](https://github.com/fabiocaccamo/django-extra-settings/releases/tag/0.1.0) - 2020-02-13
-   Released package, installation `pip install django-extra-settings`.
