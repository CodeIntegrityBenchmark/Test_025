# Test_025
This project is part of a benchmark / test suite used to check the different git histories created through different development processes. The test suite is meant to be processed by SPHA-Code-Integrity.

## Textual Description
Expected Commits against integrity rules :
* Initial Commit.
* Commit updating readme on the main branch
* Commit updating text file on the main branch after creating feature 1 branch
* Commit updating text file on main branch after creating feature 2 branch

## Changes Made In This Repo

* Make a commit updating readme on the main branch
* Create a feature-1 branch from main.
* Make a commit on the feature-1 branch.
* Make a commit on the main branch updating a file
* Create a PR wanting to merge the feature-1 branch into main branch but DO NOT Merge it.
* Create a feature-2 branch based on the main branch.
* Make a commit on the feature-2 branch
* Make a commit on the main branch updating a file
* Merge the feature-2 branch first using a PR.
* Now merge the feature-1 branch using the PR already created.
* Create an expected results branch that will be used to update the expectedResults file.
