redirector-data
===============

Data for redirections

Each folder should follow the naming convention of the Redirector 'sites' file that it supports.

e.g.

For __.......redirector/data/sites/dh.yml__ the folder should be called __dh__

For __.......redirector/data/sites/dh_immunisation.yml__ the folder should be called __dh_immunisation__

Each folder should contain 0,1 or 2 files (prefixed with the same convention)

__.......dh/dh-trump.csv__

__.......dh/dh-extras.csv__


The *-trump.csv file should have all the redirects that will trump the existing redirects (except those from the Whitehall mappings)

The *-extras.csv file should have redirects that are 'catch-all' that will generally be used to serve 410 pages that would otherwise 404 (site maps, analytics data etc.)




