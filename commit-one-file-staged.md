# **commit-one-file-staged**
Very similar challenge to the previous one.

But if you do `git status` you will get the following output:
```
On branch commit-one-file-staged
Your branch is up to date with 'origin/commit-one-file-staged'.
Changes to be committed: (use "git restore --staged <file>..." to unstage)
new file:   A.txt
new file:   B.txt
```
It means that both of the files are staged, we first have to unstage them using `git reset`.
Then it's the same as the previous challenge:)


