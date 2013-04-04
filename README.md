# Scrubbing IPython Notebook outputs

As a [git pre-commit hook](https://www.kernel.org/pub/software/scm/git/docs/githooks.html).

The goal is to avoid committing outputs to your git repo,
if that kind of thing is annoying to you.

To use:

Add `pre-commit` from this repo as `.git/hooks/pre-commit` in your repo,
and any time you commit a notebook, all outputs will be scrubbed prior to the commit
(behaves the same as the "clear all output" button in the notebook UI).
