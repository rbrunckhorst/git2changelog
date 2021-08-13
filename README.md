git2changelog
=============

# Adapted to work with python3

# Installation
pip3 install python-dateutil
python3 setup.py build
python3 setup.py install

# Purpose
git2changelog analyzes git repositories to generate formatted changelogs
# Usage
```bash
git2changelog -r REPO -b BEGIN_TAG [-e END_TAG -s SEARCH_STRING]
```
# Options
```
  -h, --help            show this help message and exit
  -b BEGIN_TAG, --begin_tag=BEGIN_TAG
                        Tag to start data collecton from. required.
  -e END_TAG, --end_tag=END_TAG
                        Tag to end the data collection. defaults to HEAD.
  -f LOG_FORMAT, --log_format=LOG_FORMAT
                        Format to Generate Changelog. defaults to rpm
  -s SEARCH_TERM, --search=SEARCH_TERM
                        Commit Search Criteria. optional.
  -n TAG_NAME, --name=TAG_NAME
                        New Tag Name for untagged commits. optional.
  -r REPO, --repo=REPO  Repository to Scan. defaults to current directory.

```
#Mailing Lists
None Yet
