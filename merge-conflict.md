# **Merge-Conflict**
Again an important concept which everyone should know how to handle.

![image](https://github.com/ayu-ch/git-exercises-writeup/assets/137001939/e4b075a0-b1a5-4ac4-b9f2-cb6585bd27ff)

When we try executing the command `git merge another-piece-of-work` we get the following output:
```
Auto-merging equation.txt
CONFLICT (content): Merge conflict in equation.txt
Automatic merge failed; fix conflicts and then commit the result.
```
Now, if you check the equation.txt it says this
```
<<<<<<< HEAD
2 + ? = 5
=======
? + 3 = 5
>>>>>>> another-piece-of-work
```
We can edit this to be `2 + 3 = 5` and then add equation.txt and commit. 

You will get the follwing output:
> [merge-conflict c712ff8] fix merge conflict

You can now git verify to see that you have solved the level:)
