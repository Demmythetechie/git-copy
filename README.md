BUNDLE 1 
#Exercise 1

C:\Users\Ejitade Isaac\Downloads\cmder
λ mkdir Gym-Git-Exercise-Solutions

C:\Users\Ejitade Isaac\Downloads\cmder
λ git init Gym-Git-Exercise-Solutions
Initialized empty Git repository in C:/Users/Ejitade Isaac/Downloads/cmder/Gym-Git-Exercise-Solutions/.g it/

C:\Users\Ejitade Isaac\Downloads\cmder
λ cd Gym-Git-Exercise-Solutions

C:\Users\Ejitade Isaac\Downloads\cmder\Gym-Git-Exercise-Solutions(master)
λ git branch -m master main

C:\Users\Ejitade Isaac\Downloads\cmder\Gym-Git-Exercise-Solutions(main)
λ cat > README.md
BUNDLE 1
Exercise 1

C:\Users\Ejitade Isaac\Downloads\cmder\Gym-Git-Exercise-Solutions(main)
λ git add -A
warning: LF will be replaced by CRLF in README.md.
The file will have its original line endings in your working directory

C:\Users\Ejitade Isaac\Downloads\cmder\Gym-Git-Exercise-Solutions(main)
λ git commit -m "Created a readme file"
[main (root-commit) ca18913] Created a readme file
1 file changed, 2 insertions(+)
create mode 100644 README.md

C:\Users\Ejitade Isaac\Downloads\cmder\Gym-Git-Exercise-Solutions(main)
λ cat ~/.ssh/id_rsa.pub
ssh-rsa AAAAB3NzaC1yc2EAAAADAQABAAABgQCybrs7J8MVAxoBzkxJ7GWquNpoQ6A1TEJOHTeSeFduSpwFi4BMta8QFTMlfK/183Tx AeS/UNKyHkoOQ1n/WzUdJhZf7Di3Sf+ewkhiJc9umsCohwVYbpazK+pQgBBg5qHGfxoPqjEdyNWcyrECugfCbqtbvugs+f4PxmZG8iSD Nb0jKSjcBLh3Fyr9yoAwOrhOUe+9fkehRhzpZidqUDe7xr+HdOe2hiL1jerdZ9KpZg/mtoRIXRsdT/YBI+tS9Du1pEvkGTTdLz+IwhkE..............

C:\Users\Ejitade Isaac\Downloads\cmder\Gym-Git-Exercise-Solutions(main)
λ git remote add orgin git@github.com:Demmythetechie/Gym-Git-Exercise-Solution.git

C:\Users\Ejitade Isaac\Downloads\cmder\Gym-Git-Exercise-Solutions(main)
λ git push git@github.com:Demmythetechie/Gym-Git-Exercise-Solution.git
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Writing objects: 100% (3/3), 240 bytes | 80.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To github.com:Demmythetechie/Gym-Git-Exercise-Solution.git

[new branch] main -> main
C:\Users\Ejitade Isaac\Downloads\cmder\Gym-Git-Exercise-Solutions(main)
λ git branch dev

C:\Users\Ejitade Isaac\Downloads\cmder\Gym-Git-Exercise-Solutions(main)
λ git checkout dev
Switched to branch 'dev'

C:\Users\Ejitade Isaac\Downloads\cmder\Gym-Git-Exercise-Solutions(dev)
λ git branch test

C:\Users\Ejitade Isaac\Downloads\cmder\Gym-Git-Exercise-Solutions(dev)
λ git branch -d test
Deleted branch test (was ca18913).

C:\Users\Ejitade Isaac\Downloads\cmder\Gym-Git-Exercise-Solutions(dev)
λ git branch

dev
main


BUNDLE 1
#Exercise 2

C:\Users\Ejitade Isaac\Downloads\cmder\Gym-Git-Exercise-Solutions(main)
λ cat > home.html
<!DOCTYPE html>
<html lang="en">
        <head>
                <title>Home</html>
        </head>
        <body>
                <div>
                        <p>This is the home page</p>
                </div>
        </body>
</html>

C:\Users\Ejitade Isaac\Downloads\cmder\Gym-Git-Exercise-Solutions(main)
λ git add home.html
warning: LF will be replaced by CRLF in home.html.
The file will have its original line endings in your working directory

C:\Users\Ejitade Isaac\Downloads\cmder\Gym-Git-Exercise-Solutions(main)
λ git stash
Saved working directory and index state WIP on main: df0bae3 deleted

C:\Users\Ejitade Isaac\Downloads\cmder\Gym-Git-Exercise-Solutions(main)
λ cat > about.html
<!DOCTYPE html>
<html lang="en">
        <head>
                <title>Home</html>
        </head>
        <body>
                <div>
                        <p>This is the about page</p>
                </div>
        </body>
</html>

C:\Users\Ejitade Isaac\Downloads\cmder\Gym-Git-Exercise-Solutions(main)
λ git add about.html
warning: LF will be replaced by CRLF in about.html.
The file will have its original line endings in your working directory

C:\Users\Ejitade Isaac\Downloads\cmder\Gym-Git-Exercise-Solutions(main)
λ git stash
Saved working directory and index state WIP on main: df0bae3 deleted

C:\Users\Ejitade Isaac\Downloads\cmder\Gym-Git-Exercise-Solutions(main)
λ cat > team.html
<!DOCTYPE html>
<html lang="en">
        <head>
                <title>Home</html>
        </head>
        <body>
                <div>
                        <p>This is the team page</p>
                </div>
        </body>
</html>

C:\Users\Ejitade Isaac\Downloads\cmder\Gym-Git-Exercise-Solutions(main)
λ git add team.html
warning: LF will be replaced by CRLF in team.html.
The file will have its original line endings in your working directory

C:\Users\Ejitade Isaac\Downloads\cmder\Gym-Git-Exercise-Solutions(main)
λ git stash
Saved working directory and index state WIP on main: df0bae3 deleted

C:\Users\Ejitade Isaac\Downloads\cmder\Gym-Git-Exercise-Solutions(main)
λ git add -A

C:\Users\Ejitade Isaac\Downloads\cmder\Gym-Git-Exercise-Solutions(main)
λ git stash list
stash@{0}: WIP on main: df0bae3 deleted
stash@{1}: WIP on main: df0bae3 deleted
stash@{2}: WIP on main: df0bae3 deleted

C:\Users\Ejitade Isaac\Downloads\cmder\Gym-Git-Exercise-Solutions(main)
λ ls
README.md

C:\Users\Ejitade Isaac\Downloads\cmder\Gym-Git-Exercise-Solutions(main)
λ git stash pop stash@{1}
On branch main
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   about.html

Dropped stash@{1} (c62da0414bdbc6ddad3321d099d89e397ca3e321)

C:\Users\Ejitade Isaac\Downloads\cmder\Gym-Git-Exercise-Solutions(main)
λ git add -A

C:\Users\Ejitade Isaac\Downloads\cmder\Gym-Git-Exercise-Solutions(main)
λ git commit -m "about.html file was unstashed"
[main 90cc27b] about.html file was unstashed
 1 file changed, 11 insertions(+)
 create mode 100644 about.html

C:\Users\Ejitade Isaac\Downloads\cmder\Gym-Git-Exercise-Solutions(main)
λ git stash pop --index 1
<stdin>:14: trailing whitespace.
                        <p>This is the home page</p>
warning: 1 line adds whitespace errors.
On branch main
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   home.html

Dropped refs/stash@{1} (2eef36cd5ae77bf6666512c87c6d6cf3f195fc5d)

C:\Users\Ejitade Isaac\Downloads\cmder\Gym-Git-Exercise-Solutions(main)
λ git add -A

C:\Users\Ejitade Isaac\Downloads\cmder\Gym-Git-Exercise-Solutions(main)
λ git commit -m "home.html file was unstashed"
[main 5585050] home.html file was unstashed
 1 file changed, 11 insertions(+)
 create mode 100644 home.html

C:\Users\Ejitade Isaac\Downloads\cmder\Gym-Git-Exercise-Solutions(main)
λ git push git@github.com:Demmythetechie/Gym-Git-Exercise-Solution.git
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 4 threads
Compressing objects: 100% (6/6), done.
Writing objects: 100% (6/6), 638 bytes | 212.00 KiB/s, done.
Total 6 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), done.
To github.com:Demmythetechie/Gym-Git-Exercise-Solution.git
   df0bae3..5585050  main -> main

C:\Users\Ejitade Isaac\Downloads\cmder\Gym-Git-Exercise-Solutions(main)
λ git stash pop --index 0
<stdin>:14: trailing whitespace.
                        <p>This is the team page</p>
warning: 1 line adds whitespace errors.
On branch main
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   team.html

Dropped refs/stash@{0} (0110c5af826fc0d9e08f6534c0f4fde5040caa69)

C:\Users\Ejitade Isaac\Downloads\cmder\Gym-Git-Exercise-Solutions(main)
λ git reset --hard
HEAD is now at 5585050 home.html file was unstashed

C:\Users\Ejitade Isaac\Downloads\cmder\Gym-Git-Exercise-Solutions(main)
λ ls
about.html  home.html  README.md



BUNDLE 2
#e[2Exercise 1
                  
BUNDLE 2
# Exercise 1

C:\Users\Ejitade Isaac\Downloads\cmder\Gym-Git-Exercise-Solutions(main)
λ git branch ft/bundle-2

C:\Users\Ejitade Isaac\Downloads\cmder\Gym-Git-Exercise-Solutions(main)
λ git checkout ft/bundle-2
Switched to branch 'ft/bundle-2'
M       README.md

C:\Users\Ejitade Isaac\Downloads\cmder\Gym-Git-Exercise-Solutions(ft/bundle-2)
λ cat > services.html
<!DOCTYPE html>
<html lang="en">
        <head>
                <title>Home</html>
        </head>
        <body>
                <div>
                        <p>This is the service page</p>
                </div>
        </body>
</html>

C:\Users\Ejitade Isaac\Downloads\cmder\Gym-Git-Exercise-Solutions(ft/bundle-2)
λ cat >> README.md

BUNDLE 2
#Exercise 1

C:\Users\Ejitade Isaac\Downloads\cmder\Gym-Git-Exercise-Solutions(ft/bundle-2)
λ git add services.html README.md
warning: LF will be replaced by CRLF in README.md.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in services.html.
The file will have its original line endings in your working directory

C:\Users\Ejitade Isaac\Downloads\cmder\Gym-Git-Exercise-Solutions(ft/bundle-2)
λ git commit -m "created a new branch and added some changes"
[ft/bundle-2 3563c8b] created a new branch and added some changes
 2 files changed, 15 insertions(+)
 create mode 100644 services.html

C:\Users\Ejitade Isaac\Downloads\cmder\Gym-Git-Exercise-Solutions(ft/bundle-2)
λ git push git@github.com:Demmythetechie/Gym-Git-Exercise-Solution.git
Enumerating objects: 6, done.
Counting objects: 100% (6/6), done.
Delta compression using up to 4 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (4/4), 543 bytes | 271.00 KiB/s, done.
Total 4 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'ft/bundle-2' on GitHub by visiting:
remote:      https://github.com/Demmythetechie/Gym-Git-Exercise-Solution/pull/new/ft/bundle-2
remote:p
To github.com:Demmythetechie/Gym-Git-Exercise-Solution.git
 * [new branch]      ft/bundle-2 -> ft/bundle-2



BUNDLE 3
#Exercise 1

using vi cleared all my history command and response but used history command in cmder to find my command history.

  git branch ft/team-page
  cat > team.html
  git add team.html
  git commit -m "Created a branch ft/team-page and a html file in it"
  git checkout main
  git  branch ft/contact-page
  git log -1
  git checkout ft/contact-page
  git cherry-pick 9a2098516ddea1b4e515fcf223d5ca6f56929631
  cat > contact.html
  git add -A
  git commit -m "cherry picked the last changes made to branch ft/team-page and added a new html file"
  git branch ft/faq-page
  git checkout ft/faq-page
  cat > faq.html
  git add faq.html
  git commit -m "Created a new branch ft/faq-page and an html file faq.html"
  git push git@github.com:Demmythetechie/Gym-Git-Exercise-Solution.git
  git checkout ft/team-page
  git revert 9a2098516ddea1b4e515fcf223d5ca6f56929631
  git add -A
  git commit -m "reverted changes of contact branch commit made to team branch previously"
  git push git@github.com:Demmythetechie/Gym-Git-Exercise-Solution.git


BUNDLE 3
#Exercise 2

C:\Users\Ejitade Isaac\Downloads\cmder\Gym-Git-Exercise-Solutions(main)
λ git checkout ft/home-page-redesign
Switched to branch 'ft/home-page-redesign'

C:\Users\Ejitade Isaac\Downloads\cmder\Gym-Git-Exercise-Solutions(ft/home-page-redesign)
λ git rebase main
Successfully rebased and updated refs/heads/ft/home-page-redesign.

C:\Users\Ejitade Isaac\Downloads\cmder\Gym-Git-Exercise-Solutions(ft/home-page-redesign)
λ sed -i "9 a \\t\t\t<p>we got all changes made to the main branch using git rebase main</p>" home.html

C:\Users\Ejitade Isaac\Downloads\cmder\Gym-Git-Exercise-Solutions(ft/home-page-redesign)
λ git add -A

C:\Users\Ejitade Isaac\Downloads\cmder\Gym-Git-Exercise-Solutions(ft/home-page-redesign)
λ git commit -m "created ft/home-page-redesign bramch and rebased all changes of main so far to it"
[ft/home-page-redesign 9996912] created ft/home-page-redesign bramch and rebased all changes of main so far to it
 1 file changed, 1 insertion(+)

C:\Users\Ejitade Isaac\Downloads\cmder\Gym-Git-Exercise-Solutions(ft/home-page-redesign)
λ git push git@github.com:Demmythetechie/Gym-Git-Exercise-Solution.git
Enumerating objects: 14, done.
Counting objects: 100% (14/14), done.
Delta compression using up to 4 threads
Compressing objects: 100% (12/12), done.
Writing objects: 100% (12/12), 1.52 KiB | 518.00 KiB/s, done.
Total 12 (delta 5), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (5/5), completed with 1 local object.
remote:
remote: Create a pull request for 'ft/home-page-redesign' on GitHub by visiting:
remote:      https://github.com/Demmythetechie/Gym-Git-Exercise-Solution/pull/new/ft/home-page-redesign
remote:
To github.com:Demmythetechie/Gym-Git-Exercise-Solution.git
 * [new branch]      ft/home-page-redesign -> ft/home-page-redesign


BUNDLE 4
#Exercise 1

C:\Users\Ejitade Isaac\Downloads\cmder\Gym-Git-Exercise-Solutions(ft/home-page-redesign)
λ git checkout main
Switched to branch 'main'

C:\Users\Ejitade Isaac\Downloads\cmder\Gym-Git-Exercise-Solutions(main)
λ git remote add git-copy git@github.com:Demmythetechie/git-copy.git

C:\Users\Ejitade Isaac\Downloads\cmder\Gym-Git-Exercise-Solutions(main)
λ sed -i "10 a \\t\t\t<p>A new remote repo (git-copy) as been created and added</p>" home.html

C:\Users\Ejitade Isaac\Downloads\cmder\Gym-Git-Exercise-Solutions(main)
λ sed -i "9 a \\t\t\t<p>A new remote repo (git-copy) as been created and added</p>" home.html

C:\Users\Ejitade Isaac\Downloads\cmder\Gym-Git-Exercise-Solutions(main)
λ git add -A

C:\Users\Ejitade Isaac\Downloads\cmder\Gym-Git-Exercise-Solutions(main)
λ git commit -m "Created a new remote repo (git-copy) as been created and added it"
[main 269eea0] Created a new remote repo (git-copy) as been created and added it
 1 file changed, 1 insertion(+)

C:\Users\Ejitade Isaac\Downloads\cmder\Gym-Git-Exercise-Solutions(main)
λ git push git@github.com:Demmythetechie/Gym-Git-Exercise-Solution.git
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 380 bytes | 380.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To github.com:Demmythetechie/Gym-Git-Exercise-Solution.git
   8d09341..269eea0  main -> main

C:\Users\Ejitade Isaac\Downloads\cmder\Gym-Git-Exercise-Solutions(main)
λ git push git@github.com:Demmythetechie/git-copy.git
Enumerating objects: 55, done.
Counting objects: 100% (55/55), done.
Delta compression using up to 4 threads
Compressing objects: 100% (51/51), done.
Writing objects: 100% (55/55), 9.17 KiB | 447.00 KiB/s, done.
Total 55 (delta 26), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (26/26), done.
To github.com:Demmythetechie/git-copy.git
 * [new branch]      main -> main


BUNDLE 4
#Exercise 2

C:\Users\Ejitade Isaac\Downloads\cmder\Gym-Git-Exercise-Solutions(main)
λ git branch ft/footer

C:\Users\Ejitade Isaac\Downloads\cmder\Gym-Git-Exercise-Solutions(main)
λ git checkout ft/footer
Switched to branch 'ft/footer'

C:\Users\Ejitade Isaac\Downloads\cmder\Gym-Git-Exercise-Solutions(ft/footer)
λ cat > footer.html
<!DOCTYPE html>
<html lang="en">
        <head>
                <title>Home</html>
        </head>
        <body>
                <div>
                        <p>This is the footer section of the home page</p>
                </div>
        </body>
</html>


C:\Users\Ejitade Isaac\Downloads\cmder\Gym-Git-Exercise-Solutions(ft/footer)
λ git add footer.html
warning: LF will be replaced by CRLF in footer.html.
The file will have its original line endings in your working directory

C:\Users\Ejitade Isaac\Downloads\cmder\Gym-Git-Exercise-Solutions(ft/footer)
λ git commit -m "Created ft/footer and footer.html branch in it"
[ft/footer 545ec40] Created ft/footer and footer.html branch in it
 1 file changed, 13 insertions(+)
 create mode 100644 footer.html

C:\Users\Ejitade Isaac\Downloads\cmder\Gym-Git-Exercise-Solutions(ft/footer)
λ sed -i "s/div/footer/g" footer.html

C:\Users\Ejitade Isaac\Downloads\cmder\Gym-Git-Exercise-Solutions(ft/footer)
λ git add footer.html

C:\Users\Ejitade Isaac\Downloads\cmder\Gym-Git-Exercise-Solutions(ft/footer)
λ git commit -m "Changed the div element in footer.html to footer element"
[ft/footer c97f697] Changed the div element in footer.html to footer element
 1 file changed, 3 insertions(+), 4 deletions(-)

C:\Users\Ejitade Isaac\Downloads\cmder\Gym-Git-Exercise-Solutions(ft/footer)
λ git push git@github.com:Demmythetechie/Gym-Git-Exercise-Solution.git
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 4 threads
Compressing objects: 100% (6/6), done.
Writing objects: 100% (6/6), 721 bytes | 360.00 KiB/s, done.
Total 6 (delta 3), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (3/3), completed with 1 local object.
remote:
remote: Create a pull request for 'ft/footer' on GitHub by visiting:
remote:      https://github.com/Demmythetechie/Gym-Git-Exercise-Solution/pull/new/ft/footer
remote:
To github.com:Demmythetechie/Gym-Git-Exercise-Solution.git
 * [new branch]      ft/footer -> ft/footer

C:\Users\Ejitade Isaac\Downloads\cmder\Gym-Git-Exercise-Solutions(ft/footer)
λ git push git@github.com:Demmythetechie/git-copy.git
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 4 threads
Compressing objects: 100% (6/6), done.
Writing objects: 100% (6/6), 721 bytes | 360.00 KiB/s, done.
Total 6 (delta 3), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (3/3), completed with 1 local object.
remote:
remote: Create a pull request for 'ft/footer' on GitHub by visiting:
remote:      https://github.com/Demmythetechie/git-copy/pull/new/ft/footer
remote:
To github.com:Demmythetechie/git-copy.git
 * [new branch]      ft/footer -> ft/footer

C:\Users\Ejitade Isaac\Downloads\cmder\Gym-Git-Exercise-Solutions(ft/footer)
λ git checkout main
Switched to branch 'main'

C:\Users\Ejitade Isaac\Downloads\cmder\Gym-Git-Exercise-Solutions(main)
λ git branch ft/squashing

C:\Users\Ejitade Isaac\Downloads\cmder\Gym-Git-Exercise-Solutions(main)
λ git checkout ft/squashing
Switched to branch 'ft/squashing'

C:\Users\Ejitade Isaac\Downloads\cmder\Gym-Git-Exercise-Solutions(ft/squashing)
λ git merge --squash ft/footer
Updating e197287..c97f697
Fast-forward
Squash commit -- not updating HEAD
 footer.html | 12 ++++++++++++
 1 file changed, 12 insertions(+)
 create mode 100644 footer.html

C:\Users\Ejitade Isaac\Downloads\cmder\Gym-Git-Exercise-Solutions(ft/squashing)
λ git commit -m "footer changes squashing"
[ft/squashing 6e90efb] footer changes squashing
 1 file changed, 12 insertions(+)
 create mode 100644 footer.html

C:\Users\Ejitade Isaac\Downloads\cmder\Gym-Git-Exercise-Solutions(ft/squashing)
λ git push git@github.com:Demmythetechie/git-copy.git
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 407 bytes | 203.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'ft/squashing' on GitHub by visiting:
remote:      https://github.com/Demmythetechie/git-copy/pull/new/ft/squashing
remote:
To github.com:Demmythetechie/git-copy.git
 * [new branch]      ft/squashing -> ft/squashing


BUNDLE 5
#Exercise 1

Done. Github page is live

