Git Perf Investigations
=======================

This repo is to assist with Git performance investigations. If you have a slow
Git command that you'd like to get faster, then please help identify more about
how Git is working for you.

To include any files that are needed for the investigation, fork this repo, 
create a branch, and create a commit containing the logs you collected based
on the steps below. Create a pull request to this repo and include a description
of your problems and the commands you ran in the PR description.

Using Trace2
------------

1. Install Git 2.20.0.
1. In your terminal window, or Git Bash on Windows:
   i. `export GIT_TRACE2=$(pwd)/trace2.txt`
   i. `export GIT_TRACE2_PERF=$(pwd)/trace2-perf.txt`
1. Run your Git command(s).
1. Create a PR including `trace2.txt` and `trace2-perf.txt`.
