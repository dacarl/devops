# Jenkins_Upgradev3
Some GIT resources
# https://docs.github.com/en/get-started/getting-started-with-git/managing-remote-repositories
To add a new remote, use the git remote add command on the terminal, in the directory your repository is stored at.

The git remote add command takes two arguments:

A remote name, for example, origin
A remote URL, for example, https://github.com/OWNER/REPOSITORY.git
For example:

$ git remote add origin https://github.com/OWNER/REPOSITORY.git
# Set a new remote

$ git remote -v
# Verify new remote
> origin  https://github.com/OWNER/REPOSITORY.git (fetch)
> origin  https://github.com/OWNER/REPOSITORY.git (push)

# Push existing repository to command line

git remote add origin https://github.com/*name*/*name*.git
git branch -M main
git push -u origin main