This is to prototype a cusp study where cusps are ID'd and digitized across multiple institutions.
Data is stored by ROI id, with the file:

* 2023/03/cusp_crossings_2026_03.csv

and the files:
* 2026/03/ROI_03309_1.csv

# Contributing to the files 
Ideally the scientists will make a clone of this area and then use Autoplot to modify
the clone, then push the results:

On a mac, initially:
* git clone git@github.com:jbfaden/cusp-study-2026.git

Then to begin a session:
* cd to the root of the local clone
* run `git pull` to get other people's changes
* run Autoplot and the <a href="https://research-git.uiowa.edu/space-physics/tracers/autoplot/-/blob/main/u/shirsh/2026/20260420/cusp_identify.jy">script</a>, loading data from the local repo
* `git status` shows what you have changed.
* `git add` adds new files to the repo.
* `git commit` to commit your changes.
* `git pull` after pushing your changes.  Note any messages about conflicts where the same region has been modified by another.
* `git push` to push your changes up to the repository.

Last the scientist should review the changes on github (https://github.com/jbfaden/cusp-study-2026/) to ensure changes are 
saved and everyone can see them.


