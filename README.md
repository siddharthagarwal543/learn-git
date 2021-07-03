# learn-git

This is a repo for demonstrating how to use git with GitHub workflows.

## Wnat to do?

1. Fork this repository.
2. Set-up a working directory and add `upstream` and `origin` remote.
3. Fetch the `upstream` remote using `git fetch upstream`.
4. Run `git branch -r` to check remote-tracking branches.
5. Create a local branch `master` tracking remote-tracking branch `upstream/master`. Use command `git checkout -b --track master upstream/master`. The word "track" in `--track` means tracking of a remote-tracking branch by a local branch, whereas in “remote-tracking branch” it means the tracking of a branch in a remote repository by the remote-tracking branch. Confusing, right?
6. If there are changes on `master` in the future, fetch and merge `upstream/master` in your local `master` branch. First fetch upstream using `git fetch upstream`. Then checkout to your local `master` branch using `git checkout master`. Then, merge `upstream/master` using `git merge upstream/master`
7. Create a local feature branch e.g. `first-patch`
8. Make whatever changes you want to. e.g. add a Python program to perform binary search. or make changes to this file. I have planted some typos for you. (or have I :))
9. Push the changes to your fork i.e. push a remote-tracking branch to `origin` with the same name as your local feature branch.
10. Create a pull request.
