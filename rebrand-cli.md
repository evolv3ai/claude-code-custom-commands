We are going to create a new CLI tool.

We cloned a commanderjs template repo here and now we will rebrand it for our project.

Here is the current file tree:

!`git tree --gitignore`

Follow each step one-by-one:
- Delete the .git folder with `git rm -rf ./.git`
- Run `git init` to re-initialize the repo
- Run `commit-creator` in the project repo, it can take a while so set a high timeout
- Stop and ask me what the title and name of new CLI tool will be
    - The message should be "Please enter the title and name of your new CLI tool:"
- Go through the entire repo and rebrand everything about "commanderjs template" to use the project name and title you provided
  - Search through the project deeply making sure it is full rebranded
- Run `commit-creator` again to save the rebranding
