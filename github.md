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