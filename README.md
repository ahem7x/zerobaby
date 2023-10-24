# zerobaby
echo "# zerobaby" >> README.md
git init


Initialized empty Git repository in /home/ahem/gitz/zerobaby/.git/

git add .
touch README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/ahem7x/zerobaby.git
Enter username and  personalised token
git push -u origin main

Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Writing objects: 100% (3/3), 216 bytes | 216.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/ahem7x/zerobaby.git
 * [new branch]      main -> main
Branch 'main' set up to track remote branch 'main' from 'origin'.
ahem@devx:~/gitz/zerobaby$ 

Add steps to README.md 

git commit -m " steps to checkin and build"


git push

Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 16 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 392 bytes | 392.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/ahem7x/zerobaby.git
   842ee6d..2319999  main -> main


https://blog.logrocket.com/ci-cd-node-js-github-actions/


Make changes to the code in the local repo and make changes to the readme in the main through GitHub UI.

You to have rebase before pushing the code.

ahem@devx:~/gitz/zerobaby$ git pull origin --rebase
Successfully rebased and updated refs/heads/main.
ahem@devx:~/gitz/zerobaby$ git push -u origin main
Enumerating objects: 12, done.
Counting objects: 100% (12/12), done.
Delta compression using up to 16 threads
Compressing objects: 100% (9/9), done.
Writing objects: 100% (11/11), 77.99 KiB | 13.00 MiB/s, done.
Total 11 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/ahem7x/zerobaby.git
   a4b93d2..95b0f8e  main -> main
Branch 'main' set up to track remote branch 'main' from 'origin'.
ahem@devx:~/gitz/zerobaby$ 





