# Working Repo

## Creating local repository

- `cd <folder-location>`
- `git init`
- `git add .`
- `git commit -m "some message !!`
-

![enter image description here](https://kevintshoemaker.github.io/StatsChats/GIT2.png)

## Add a New Remote to your Git Repo

- Create a New repository in your GitHub
  ![enter image description here](https://d186loudes4jlv.cloudfront.net/git/images/github_new_repo2.png)

- Copy the remote repo URL which can find on the Source sub-tab of your Git repo

![enter image description here](https://github-images.s3.amazonaws.com/enterprise/2.13/assets/images/help/repository/remotes-url.png)

- open your local repository in Terminal
- `git remote add <remote-name> <remote-url>`

## Update the Remote repository

    git push -u <remote-name> <remote-branch>
