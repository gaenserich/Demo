# Demo
A demonstration repository! Here are the things I want to demonstrate:

1. **The "Undo" functionality of git.**

In the work directory, execute the following commands after modifying this file:
```shell
git add -A                ## This makes git save chagnes
git commit -m '[message]' ## This annotates all saved but not-yet-annototed changes into a "commit," complete with a comment 'message'
git log                   ## This shows a list of all the commits made, and which can be undone
git checkout [commit] .   ## This changes the contained files back to the particular commit
```

