# Demo project README

This is a simple readme file

# making a change
make another change

adding a branch

kat_o@KM-C15M MINGW64 ~/projects/demo (master)
$ git status
On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md

no changes added to commit (use "git add" and/or "git commit -a")

kat_o@KM-C15M MINGW64 ~/projects/demo (master)
$ git branch
* master

kat_o@KM-C15M MINGW64 ~/projects/demo (master)
$ git checkout -b updates
Switched to a new branch 'updates'

kat_o@KM-C15M MINGW64 ~/projects/demo (updates)
$ git add .

kat_o@KM-C15M MINGW64 ~/projects/demo (updates)
$ git commit -m
error: switch `m' requires a value

kat_o@KM-C15M MINGW64 ~/projects/demo (updates)
$ git commit -m "Adding updates from branch"
[updates be103e2] Adding updates from branch
 1 file changed, 3 insertions(+)

kat_o@KM-C15M MINGW64 ~/projects/demo (updates)
$ git hist
* be103e2 (HEAD -> updates) Adding updates from branch
* 98e2cf5 (master) Adding ignore file
* 2eb0aac remove myfile.txt
* a61b54d rename and add
* b9cf7a8 deleting demo file
* 110023c Renaming example to demo
* 9cfe002 adding example.txt
* fed65d7 Updating README
* 0abee72 added readme and license file

kat_o@KM-C15M MINGW64 ~/projects/demo (updates)
$ git diff updates master
diff --git a/README.md b/README.md
index b000a4d..df12a80 100644
--- a/README.md
+++ b/README.md
@@ -3,6 +3,3 @@
 This is a simple readme file

 # making a change
-make another change
-
-adding a branch
\ No newline at end of file

kat_o@KM-C15M MINGW64 ~/projects/demo (updates)
$

