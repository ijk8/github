This document describes the fastest way to get started with git and
github. After creating your
[repository](https://help.github.com/articles/create-a-repo/), run these
commands on a computer where you have git installed. Make sure to adjust
the names first.
```
git clone https://githubusername:githubpassword@github.com/githubusername/repositoryname.git
cd repositoryname
git config user.name "githubusername"
git config user.email "githubconfiguredmail@example.com"
git config push.default simple
```
You might now want to add some files to `repositoryname`.
```
echo hello > greeting.txt
git add .
git commit -m "add file"
```
Run `git push` and edit `greeting.txt` in github. Once that's done, run
`git pull` and verify that the changes have been applied to your local
copy of `greeting.txt`.
