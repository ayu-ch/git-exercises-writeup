# **Save-your-work**

```
Instructions
You are working hard on a regular issue while your boss comes in and wants you to fix a bug. State of your current working area is a total mess so you don't feel comfortable with making a commit now. However, you need to fix the found bug ASAP.

Git lets you to save your work on a side and continue it later. Find appropriate Git tool and use it to handle the situation appropriately.

Look for a bug to remove in bug.txt.

After you commit the bugfix, get back to your work. Finish it by adding a new line to bug.txt with:
Finally, finished it!
Then, commit your work after bugfix.
```
>## Git stash
>`git stash` temporarily shelves (or stashes) changes you've made to your working copy so you can work on something else, and then come back and re-apply them later on. Stashing is handy if you need to quickly switch context and work on something else, but you're mid-way through a code change and aren't quite ready to commit.
>You can learn more about this [here](https://www.atlassian.com/git/tutorials/saving-changes/git-stash#stashing-your-work)

If we check the status by `git status` we can see two files are unstaged: **bug.txt** and **program.txt** respectively.

First we have to change only the bug which is in the bug.txt, we can do this by saving our work by using the command `**git stash**`.

If we try to see the status now, we can see we have nothing to commit.

The contents of the bug.txt says the following:
```
This file contains bug
It has to be somewhere.
I feel like I can smell it.
THIS IS A BUG - remove the whole line to fix it.
How this program could work with such bug?
```
We have to remove the 4th line and then commit.

To return back to our saved work, we can use `git stash pop` . This will again make our files unstaged.

But now, we have fixed our bug! According to the instructions, we have to add the respective line and then add,commit and verify.

