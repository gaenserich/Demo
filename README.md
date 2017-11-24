# Demo
A demonstration repository! Here are the things I want to demonstrate:

1. **The "Undo" functionality of git.** In the work directory, execute the following commands after modifying this file:
```shell
git status                ## This tells us what's going on
git add -A                ## This makes git save changes
git commit -m '[message]' ## This annotates all saved but not-yet-annototed changes into a "commit," complete with a comment 'message'
git log                   ## This shows a list of all the commits made, and which can be undone
git checkout [commit] .   ## This changes the contained files back to the particular commit
```

2. **Git's ability to synchronize.** Let's re-upload this README to GitHub, modify it on GitHub, and then synchronize it back:
```shell
git push -u --all         ## Upload all commits to pre-configured repositories, here, a github account.
```
Go modify this on github now
```shell
git pull                  ## Download and merge all changes
```
3. **Git's collaborative abilities.** Notice how multiple people could edit the same line and upload it at the same time. Git can fix that!

Crosby, Stills, and Nash
