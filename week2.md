# Week 2 Git Homework

Working on branch week2 - step 1
Working on branch week2 - step 2
This line was added on week2 branch.

===== PART D - REBASE =====



Before the rebase, master and experiment had different commits.



The experiment branch had two commits:

\- Add experiment file 1

\- Add experiment file 2



The master branch had another commit:

\- Add main file



After running "git rebase experiment" while on master, the master

commit was moved to the top of the experiment history. This created

a linear history.



The commit hash of "Add main file" changed because rebase creates

a new commit based on the new parent commit.

