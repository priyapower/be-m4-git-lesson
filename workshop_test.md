## Exercise 1

#### The rebase workflow has a lot of similarities to the merge workflow, especially around resolving conflicts that arise when multiple contributors are working on the same codebase. While there are a few different ways of doing this, we’ll cover one way you can approach it.

1. Checkout a new branch (branch1) off of master and make some edits by adding or removing methods from files or creating new files with some content.
2. Create 3 new commits on this branch (branch1). Run git log and note the three new commits that you have added.
3. Checkout another branch (branch2) off of master and make some edits here as well. You only need to create 1 new commit on this branch.
4. Next, go back to your previous branch (branch1), and push up your branch to GitHub with git push origin <branch_name>. Then go to your GH repo and click Compare & pull request.
5. When you open the pull request, change the base repository to be your repository. (NOT Turing!). Then click Create pull request.
