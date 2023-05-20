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
