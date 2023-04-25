
To reset a branch to a previous commit in GitHub, you can use the following commands:

1. First, make sure you're on the branch you want to reset. You can switch to the branch by running the following command:
```
git checkout branch-name
```

2. Next, identify the commit hash that you want to reset the branch to. You can find this hash by running `git log` and looking for the commit you want to reset to.

3. Once you have the commit hash, you can reset the branch by running one of the following commands, depending on what you want to do:

   - To reset the branch to a specific commit and discard all changes after that commit, use the following command:
   ```
   git reset --hard commit-hash
   ```

   - To reset the branch to a specific commit but keep all changes after that commit as uncommitted changes, use the following command:
   ```
   git reset --soft commit-hash
   ```

4. Finally, push the changes to the remote repository using the following command:
```
git push --force origin branch-name
```

Note that the `--force` flag is required to overwrite the remote branch with your changes, so be careful when using this command. It's generally a good idea to create a backup branch or tag before resetting the branch to ensure that you don't lose any important changes.
