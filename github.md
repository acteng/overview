# Using GitHub in Active Travel England

This is a guide to using GitHub in Active Travel England.
We use a process called Git Flow to manage our work.

The process is as follows:

1. Create an issue in GitHub
  - For example, this document was created in support of https://github.com/acteng/overview/issues/29
2. Create a branch for the issue
  - With the gh command line tool you can do this as follows:
    - `gh issue develop 29 --checkout`
    - You should now be on the new branch, the command above for example created this branch: https://github.com/acteng/overview/tree/29-documentation-on-how-we-use-github
    - Do your work in the branch, adding commits regularly and with clear commit messages to document your work
3. Create a pull request
  - With the gh command line tool you can do this as follows:
    - `gh pr create`
    - This will open your default browser to the pull request page, where you can add a description of the work you have done
    - You can also add reviewers to the pull request, for example if you want someone to review your work before it is merged
