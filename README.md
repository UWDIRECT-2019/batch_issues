# batch_issues

[![DOI](https://zenodo.org/badge/227898447.svg)](https://zenodo.org/badge/latestdoi/227898447)

A utility script for the batch submission of issues for grading homeworks via
Github.

## How to use

This script will batch submit the homework grading issues for all Github
repos (student homework repos) in the current path. This is to be used
after you have graded all the homework repos on your local machine by
modifying the ```ISSUE_TEMPLATE.md``` file that is automatically generated
in the homework repos. It eliminates the need to manually create an issue
and fill out the grade online in github/github classroom.

## Additional Requirements

Use of this script requires installation of the [`github/hub`](https://github.com/github/hub) tool. This enables the creation and submission of issues via command line.
