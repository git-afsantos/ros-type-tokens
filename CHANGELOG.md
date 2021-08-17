# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](http://semver.org/spec/v2.0.0.html).

## v0.1.2 - 2021-08-17
### Fixed
- Python 3 compatibility bug; some code still used `long`.

## v0.1.1 - 2021-08-06
### Fixed
- `MANIFEST.in` was missing `requirements.txt`, causing an issue when installing with `pip`.
