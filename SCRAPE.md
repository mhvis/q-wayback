# Scrape notes

Command: `wget --mirror --convert-links --page-requisites --execute robots=off --adjust-extension --no-verbose --no-parent http://host 2>&1 | grep -i -B 1 "failed\|error"`

* Check character encoding of the file and also declarations in `meta` tags.
* Check in the browser for 404 errors.
* The command only scrapes the URL directory given, check for missed domains or directories.
* Remove Google Analytics or Facebook scripts.
