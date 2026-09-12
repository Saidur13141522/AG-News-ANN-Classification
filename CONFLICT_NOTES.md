# Merge Conflict Notes

## What caused the conflict?

A merge conflict was intentionally created in `README.md` as part of the project requirements.

The same first line of the README was modified differently on the `main` and `proposal` branches.

The `main` branch contained:

> AG News Classification Project - Main Branch Version

The `proposal` branch contained:

> AG News ANN Text Classification - Proposal Version

Because both branches modified the same line differently, Git could not automatically determine which version should be kept.

## How was the conflict resolved?

The conflict was resolved manually on the `proposal` branch.

The conflicting versions were replaced with the final combined project title:

> AG News Topic Classification Using an Artificial Neural Network

The Git conflict markers were removed, the corrected README was staged, and a new commit was created.

The resolution was then pushed to GitHub so that the pull request could be merged.

## Resolution Commit

The conflict was resolved using the commit:

`Resolve README merge conflict`
