Makswell5@Makswell5_PC1 MINGW64 /d/сайты/barder_shop (master)
$ git add Readme.md
fatal: pathspec 'Readme.md' did not match any files

Makswell5@Makswell5_PC1 MINGW64 /d/сайты/barder_shop (master)
$ git add Readme.md

Makswell5@Makswell5_PC1 MINGW64 /d/сайты/barder_shop (master)
$ git commit -m "first commit"
[master (root-commit) 9b1d2fe] first commit
 1 file changed, 1 insertion(+)
 create mode 100644 Readme.md

Makswell5@Makswell5_PC1 MINGW64 /d/сайты/barder_shop (master)
$ git push origin master
Counting objects: 3, done.
Writing objects: 100% (3/3), 215 bytes | 71.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0)
To github.com:makswell5/barder_shop.git
 * [new branch]      master -> master

Makswell5@Makswell5_PC1 MINGW64 /d/сайты/barder_shop (master)
$ git pull
Already up-to-date.

Makswell5@Makswell5_PC1 MINGW64 /d/сайты/barder_shop (master)
$ git checkout -b adaptive
Switched to a new branch 'adaptive'

Makswell5@Makswell5_PC1 MINGW64 /d/сайты/barder_shop (adaptive)
$ git add Readme.md

Makswell5@Makswell5_PC1 MINGW64 /d/сайты/barder_shop (adaptive)
$ git commit -m "Refresh history"
On branch adaptive
nothing to commit, working tree clean

Makswell5@Makswell5_PC1 MINGW64 /d/сайты/barder_shop (adaptive)
$ git commit -m "Обновил описание"
On branch adaptive
nothing to commit, working tree clean

Makswell5@Makswell5_PC1 MINGW64 /d/сайты/barder_shop (adaptive)
$ git checkout master
Switched to branch 'master'
Your branch is up-to-date with 'origin/master'.

Makswell5@Makswell5_PC1 MINGW64 /d/сайты/barder_shop (master)
$ git add Readme.md

Makswell5@Makswell5_PC1 MINGW64 /d/сайты/barder_shop (master)
$ git commit -m "Обновил описание"
On branch master
Your branch is up-to-date with 'origin/master'.

nothing to commit, working tree clean

Makswell5@Makswell5_PC1 MINGW64 /d/сайты/barder_shop (master)
$ git checkout adaptive
Switched to branch 'adaptive'

Makswell5@Makswell5_PC1 MINGW64 /d/сайты/barder_shop (adaptive)
$ git add Readme.md

Makswell5@Makswell5_PC1 MINGW64 /d/сайты/barder_shop (adaptive)
$ git commit -m "Обновил описание"
[adaptive f259102] Обновил описание
 1 file changed, 1 insertion(+), 1 deletion(-)

Makswell5@Makswell5_PC1 MINGW64 /d/сайты/barder_shop (adaptive)
$ git push origin adaptive
Counting objects: 3, done.
Writing objects: 100% (3/3), 298 bytes | 298.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0)
To github.com:makswell5/barder_shop.git
 * [new branch]      adaptive -> adaptive

Makswell5@Makswell5_PC1 MINGW64 /d/сайты/barder_shop (adaptive)
$ git checkout origin/adaptive -b adptive
Switched to a new branch 'adptive'
Branch adptive set up to track remote branch adaptive from origin.

Makswell5@Makswell5_PC1 MINGW64 /d/сайты/barder_shop (adptive)
$ git checkout origin/adaptive -b adaptive
fatal: A branch named 'adaptive' already exists.

Makswell5@Makswell5_PC1 MINGW64 /d/сайты/barder_shop (adptive)
$ git commit -m "Обновил описание"
On branch adptive
Your branch is up-to-date with 'origin/adaptive'.

Changes not staged for commit:
        modified:   Readme.md

no changes added to commit

Makswell5@Makswell5_PC1 MINGW64 /d/сайты/barder_shop (adptive)
$ git checkout master
error: Your local changes to the following files would be overwritten by checkout:
        Readme.md
Please commit your changes or stash them before you switch branches.
Aborting

Makswell5@Makswell5_PC1 MINGW64 /d/сайты/barder_shop (adptive)
$ git checkout master
error: Your local changes to the following files would be overwritten by checkout:
        Readme.md
Please commit your changes or stash them before you switch branches.
Aborting

Makswell5@Makswell5_PC1 MINGW64 /d/сайты/barder_shop (adptive)
$ git checkout -m master
Switched to branch 'master'
M       Readme.md
Your branch is up-to-date with 'origin/master'.

Makswell5@Makswell5_PC1 MINGW64 /d/сайты/barder_shop (master)
$ git add Readme.md

Makswell5@Makswell5_PC1 MINGW64 /d/сайты/barder_shop (master)
$ git commit -m "Обновил описание"
[master 529fbc4] Обновил описание
 1 file changed, 4 insertions(+), 1 deletion(-)

Makswell5@Makswell5_PC1 MINGW64 /d/сайты/barder_shop (master)
$ git push origin master
Counting objects: 3, done.
Writing objects: 100% (3/3), 316 bytes | 316.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0)
To github.com:makswell5/barder_shop.git
   9b1d2fe..529fbc4  master -> master

Makswell5@Makswell5_PC1 MINGW64 /d/сайты/barder_shop (master)
$ git checkout origin/adaptive -b adaptive
fatal: A branch named 'adaptive' already exists.

Makswell5@Makswell5_PC1 MINGW64 /d/сайты/barder_shop (master)
$ git checkout adptive
Switched to branch 'adptive'
Your branch is up-to-date with 'origin/adaptive'.

Makswell5@Makswell5_PC1 MINGW64 /d/сайты/barder_shop (adptive)
$ git branch
  adaptive
* adptive
  master

Makswell5@Makswell5_PC1 MINGW64 /d/сайты/barder_shop (adptive)
$ git branch -d adptive
error: Cannot delete branch 'adptive' checked out at 'D:/сайты/barder_shop'

Makswell5@Makswell5_PC1 MINGW64 /d/сайты/barder_shop (adptive)
$ git checkout master
Switched to branch 'master'
Your branch is up-to-date with 'origin/master'.

Makswell5@Makswell5_PC1 MINGW64 /d/сайты/barder_shop (master)
$ git branch -d adptive
warning: deleting branch 'adptive' that has been merged to
         'refs/remotes/origin/adaptive', but not yet merged to HEAD.
Deleted branch adptive (was f259102).

Makswell5@Makswell5_PC1 MINGW64 /d/сайты/barder_shop (master)
$ git branch
  adaptive
* master

Makswell5@Makswell5_PC1 MINGW64 /d/сайты/barder_shop (master)
$  git chout origin/adaptive -b adaptive
git: 'chout' is not a git command. See 'git --help'.

The most similar command is
        checkout

Makswell5@Makswell5_PC1 MINGW64 /d/сайты/barder_shop (master)
$ git checkout origin/adaptive -b adaptive
fatal: A branch named 'adaptive' already exists.

Makswell5@Makswell5_PC1 MINGW64 /d/сайты/barder_shop (master)
$ ^C

Makswell5@Makswell5_PC1 MINGW64 /d/сайты/barder_shop (master)
$ git cheout adaptive
git: 'cheout' is not a git command. See 'git --help'.

The most similar command is
        checkout

Makswell5@Makswell5_PC1 MINGW64 /d/сайты/barder_shop (master)
$ gitt checkout adaptive
bash: gitt: command not found

Makswell5@Makswell5_PC1 MINGW64 /d/сайты/barder_shop (master)
$ git checkout adaptive
Switched to branch 'adaptive'

Makswell5@Makswell5_PC1 MINGW64 /d/сайты/barder_shop (adaptive)
$ git checkout master
Switched to branch 'master'
Your branch is up-to-date with 'origin/master'.

Makswell5@Makswell5_PC1 MINGW64 /d/сайты/barder_shop (master)
$ git merge adaptive
Auto-merging Readme.md
CONFLICT (content): Merge conflict in Readme.md
Automatic merge failed; fix conflicts and then commit the result.

Makswell5@Makswell5_PC1 MINGW64 /d/сайты/barder_shop (master|MERGING)
$ git add Readme.md

Makswell5@Makswell5_PC1 MINGW64 /d/сайты/barder_shop (master|MERGING)
$ git commit -m "perezaliv"
[master 3bf50a7] perezaliv

Makswell5@Makswell5_PC1 MINGW64 /d/сайты/barder_shop (master)
$ git push
Counting objects: 3, done.
Delta compression using up to 2 threads.
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 314 bytes | 157.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0)
To github.com:makswell5/barder_shop.git
   529fbc4..3bf50a7  master -> master

Makswell5@Makswell5_PC1 MINGW64 /d/сайты/barder_shop (master)
$
