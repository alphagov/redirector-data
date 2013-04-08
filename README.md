redirector-data
===============

Data for redirections

Each folder should follow the naming convention of the Redirector 'sites' file that it supports.

e.g.

For .......redirector/data/sites/dh.yml the folder should be called dh
For .......redirector/data/sites/dh_immunisation.yml the folder should be called dh_immunisation

Each folder should contain 0,1 or 2 files (prefixed with the same convention)

.......dh/dh-trump.csv
.......dh/dh-extras.csv

The *-trump.csv file should have all the redirects that will trump the existing redirects (except those from the Whitehall mappings)
The *-extras.csv file should have redirects that are 'catch-all' that will generally be used to serve 410 pages that would otherwise 404 (site maps, analytics data etc.)




