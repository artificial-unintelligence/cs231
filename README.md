# cs231
Dumping ground for homework of cs231


# How to create code review?

## Create a branch for changes
```
git checkout -b [your-branch-name]
```
This will help you create a branch and switch to that branch.

## Modify the code in that branch
You can check the branch you are currently on by `git branch`. The name with a * in the front is the branch you are currently on.

Once you ensure you are on the designated branch, then you can modify the homework code.

## Commit changes and push to remote branch
Whenever you complete a self-contained change, commit and push it to the remote branch. Don't be afraid the change is too small to commit, as long as it is self-contained. **At least, commit at the end of the day**

For the first time you push, you need to create a remote branch that track the local one you created.
```
git push -u origin [your-branch-name]
```

After this, you could use `git push` to push your local branch to remote tracking branch.

## Create pull request for code review
When you think your code is good enough for a code review, make sure you commit and push all the changes, go ahead and create a pull request.

To create a pull request, go to the [repository's compare page](https://github.com/artificial-unintelligence/cs231/compare). Select your branch in the **compare:** drop down menu and review the changes. If everything looks right, then go ahead and hit **create pull request** button.

## Add reviewer to the pull request
Aka, me.


# How to review code?

Well, this is a long topic. I will add something later...

