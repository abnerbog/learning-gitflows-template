At this point, we have made our file changes and are satisfied with the state of our local repository. It is time to join these changes with the main repository so that our collaborators can use them. Before we can merge our changes with the main repository, we need to get our local changes onto our fork on GitHub.

----
**Action:** Push your changes to your GitHub fork. 

1. If you run `git status` in Git Bash  right now, you should see a message that says "nothing to commit" and also "Your branch is ahead of 'origin/main' by 2 commits". This means that our local version has 2 new changes that do not appear in our remote fork (called the `origin` because our local version *originated* from it). 
1. Go to your fork's webpage (`https://github.com/[username]/learning-gitflows-[username]`) and click on the `X commits` button (see image below). At this time, you should only see commits that occurred before you started working on the repository (instructors prepped the repo by making commits).
1. To get our local changes to appear on our remote fork, we need to "push" them there. To do so, run `git push`. By default, it will push changes up to the `origin` remote `main` branch (we aren't using branching just yet, so everything is the `main` branch). If you want to be more explicit, you can run `git push [remote name] [branch name]`. For example, `git push origin main` will do the same as `git push`.
1. After you run this successfully, you will see `To github.com:[username]/learning-gitflows-[username].git` near the bottom. It is telling you where those changes went, which is to your remote fork. Yay!
1. Go to your fork's webpage (`https://github.com/[username]/learning-gitflows-[username]`) and click on the `X commits` button (see image below). You should see your two commit messages appear there.

![image](https://github.com/CUAHSI/learning-gitflows-template/assets/13220910/6d19c388-6332-486b-b82e-3c8794a79f5e)

You have pushed your changes up to GitHub! Close this issue and move on to the next one.
