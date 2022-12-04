

# Git学习笔记

## Commands List

For simplicity, there are no ideas of how to use these commands here.

```python
git clone
git status
git add
git commit -m ""
git push    

git init
git branch
git merge
git checkout
git pull
git diff

git log
git diff
git help
```

## Some Notes

疑惑：对于 `git merge` ， `git checkout` 具体干了什么，我依然不清楚。

It sames that all of these command:

- `git merge` 
- `git checkout`
- `git pull` 

will not change my `.py` file directory.

What is the status of multiple branches in a project folder?

I found that I can back to the status of my latest commit in a branch.  Commit means save the changes, and the simply changing of files means nothing.

Now, Git is a little complex for me. But I could just move on.

Oh! I'm amazing to find that when I delete a python file, and checkout to another branch and checkout back to the initial one, the file is back too. What should I do to delete a file which is committed? 

You could try again and again if you failed to use `git push` . It may have something to do with probability.

You can press `q` to terminate the command of `git log` .

It is so strange that I can sign in Github but failed with `git clone` .

You can create a new branch named "new_feature" with `git checkout -b new_feature` , and work with it after `git push --set-upstream origin new_feature` .