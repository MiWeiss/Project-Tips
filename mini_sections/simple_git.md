## Let git help you with your project
Obviously, you should use git for any of your projects.
The following recommendations help you to get the most out of git.
They assume you know how to work with git and in particular with different branches.
If you don't know git well and don't want to learn it now, just ignore this page.

1. **Keep the `main` branch always clean:** Make sure code on the main branch always compiles 
    and does not break any functionality that worked in previous versions.
    Like that, you have always a version ready to submit for milestone discussions.
2. **Implement new features on distinct branches** and merge them into main when the feature is completely implemented.
    Keeping features as small as possible or dividing them into sub-features (and thus merging early and often) 
    helps you to avoid merge conflicts.
3. **Commit and Push often**. This makes sure you don't lose much if your PC crashes. 
    Also, if you mess up you can always just go back to a previous version and try again 
    (e.g. `git revert` to discard uncommitted changes).
    Run your unit tests whenever you commit to make sure your changes did not introduce any new bugs on existing code.
