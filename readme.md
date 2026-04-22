This is to prototype a cusp study where cusps are ID'd and digitized across multiple institutions.
Data is stored by ROI id, with the file:

* 2025/cusp_crossings.csv

and the files:
* 2025/ROI_01212_1.csv
* 2026/ROI_02405_1.csv

# Contributing to the files 
Ideally the scientists will make a clone of this area and then use Autoplot to modify
the clone, then push the results:

On a mac, initially:
* git clone git@github.com:jbfaden/cusp-study-2026.git

Then to begin a session:
* cd to the root of the local clone
* run "git pull" to get other people's changes
* run Autoplot, loading data from the local repo
* run "git commit" to commit your changes.
* run "git pull" before committing your changes.  Note any messages about conflicts where the same region has been modified by another.
* run "git push" to push your changes up to the repository.
