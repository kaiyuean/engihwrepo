CSCI 5828 - Fall 2015

Homework2

Kaiyue An

This is a git repo that produces the commit graph in homework2.

Third edit.

Fourth edit.

First edit.

Second edit.

Ninth edit.

Fifth edit.

Sixth edit.

Seventh edit.

Eighth edit.

Tenth edit.

All the git commands I used to create this repo:

mkdir engihwrepo; cd engihwrepo; git init;

vi README.md; git add README.md; git commit -m "Initial commit"; git show;

vi README.md; git add README.md; git commit -m "Second commit";

vi README.md; git add README.md; git commit -m "Third commit"; git show;

git checkout 42f7065fe5715edd673b23bcd4843f7527c31479;

git checkout -b bug-fix;

vi README.md; git add README.md; git commit -m "Fourth commit";

vi README.md; git add README.md; git commit -m "Fifth commit"; git show;

git merge 80e67496b9bb8b21061ce3c3e61662d0760ccff9; vi README.md; git add RE    ADME.md; git commit -m "Fixed Conflict";

vi README.md; git add README.md; git commit -m "Seventh commit";

git checkout 4c2df171f95931895ed5ac16a22f0a8efef7cc5c;

git checkout -b bug-fix-experimental;

vi README.md; git add README.md; git commit -m "Eighth commit";

vi README.md; git add README.md; git commit -m "Ninth commit";

vi README.md; git add README.md; git commit -m "Tenth commit";

git checkout master;

vi README.md; git add README.md; git commit -m "Eleventh commit";

git checkout bug-fix;

git merge bug-fix-experimental; vi README.md; git add README.md; git commit -m "Fixed Conflict";

vi README.md; git add README.md; git commit -m "Thirteenth commit";

git checkout master;

git merge bug-fix; vi README.md; git add README.md; git commit -m "Fixed Conflict";

vi README.md; git add README.md; git commit -m "Fifteenth commit";
