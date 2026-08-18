On branch master
Untracked files:
  (use "git add <file>..." to include in what will be committed)
	./

nothing added to commit but untracked files present (use "git add" to track)
===== STATUS AFTER STAGING =====
On branch master

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)

        new file:   part1/notes.txt
        new file:   part1/todo.txt

Untracked files:
  (use "git add <file>..." to include in what will be committed)

        part1/draft.md
        part1/status_log.md

no changes added to commit
===== GIT DIFF - UNSTAGED CHANGE =====
diff --git a/part1/notes.txt b/part1/notes.txt
index e69de29..977ff88 100644
--- a/part1/notes.txt
+++ b/part1/notes.txt
@@ -0,0 +1,3 @@
+Git is a version control system.
+Git helps track changes in files.
+GitHub hosts Git repositories online.
===== GIT DIFF --STAGED =====
diff --git a/part1/notes.txt b/part1/notes.txt
index e69de29..977ff88 100644
--- a/part1/notes.txt
+++ b/part1/notes.txt
@@ -0,0 +1,3 @@
+Git is a version control system.
+Git helps track changes in files.
+GitHub hosts Git repositories online.
===== FETCH VS PULL =====

git fetch downloads new commits from the remote repository and updates
the remote-tracking branch, such as origin/master. It does not merge
the changes into the current local branch.

git pull performs git fetch and then integrates the fetched changes
into the current local branch.
