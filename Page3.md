# Other assignment questions
## Undoing a Git commit
This can be easily accomplished using the `reset` command. The two options for doing this are
1. `git reset --soft HEAD~n` 
2. `git reset --hard HEAD~n` 
Where _n_ is the number of commits that you would like to undo. The difference between `soft` and `hard` is that the 
former keeps changes as uncommitted and the latter discards all changes after the specified HEAD state.

## A detached HEAD state
A detached head state can be fixed by returning to the master branch using `git checkout master`. 
