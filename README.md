# Git Skip Worktree Manager README

An extension to manage the `git update-index --skip-worktree` Git command.

## Features

![Image](images\image.gif)

The following three methods can be used to register a file for `skip-worktree`.

- Adding a file with the Git command
- Right-click the file in Explorer and select `Skip Worktree Toggle`.
- Define it in `gitSkipWorktreeManager.paths` in setting.json
- On the `GIT UPDATE INDEX MANAGER` tab, click the `+` button next to the file name.

If you want to disable all files registered in the SkipWorktree, click the `All Git Skip Worktree Disable` button on the status bar.

## Requirements

Have a Git version installed that can use `git update-index --skip-worktree`.

## Extension Settings

By defining files in `gitSkipWorktreeManager.paths` as relative paths from the workspace, you can make them the default target files for the workspace.

``` setting.json
{
  "gitSkipWorktreeManager.paths": []
}
```

## Release Notes

### 1.0.0

Initial release
