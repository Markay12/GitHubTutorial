## Understanding

Git is version control software on a machine that does not require and internet connection.

GitHub hosts git repositories in the cloud so that other people can access and use your code.

## Git Repositories

A git repository, often referred to as a repo, is a workspace which tracks and manages files in a folder. This folder has its own history, like a notebook with a table of contents.

### Creating a New Repository

To create a new repository, one must access their own account on GitHub's site and initialize one. You will then select a name for the repository, which folder you would like to keep it in and a description for it. I would recommend that you initizalize your repo's with a README file.

To access information about your repo and its files you can use the command `git status` in the command line. This command will give information about the current repo and its contents.

To create a new repository from the command line you can use `git init`. This repo will be created in the same directory you are already located in. This new repository will begin with nothing in it, therefore, it is good to start with `git status` once created.

After the initial repo has been created an initial `.git` folder is created. This is a hidden folder where the git configuration amongst other things is held. This folder is hidden because it holds all of the repo history.

> WARNING: DO NOT CREATE A REPOSITORY INSIDE A REPOSITORY
