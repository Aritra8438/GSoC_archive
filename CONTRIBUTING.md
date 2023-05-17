## Contribution Workflow:

Hello contributors, here is the contribution guideline you should follow:

- **First, create a fork of this repo. (Available at the top right corner of the repo)** 

- Go to the forked repository and **Clone your fork of your repo to the destination folder**.
```
$ git clone https://github.com/YOUR_USERNAME/YOUR_FORK.git

```
- Add Upstream to your clone

```
$ git remote -v
> origin  https://github.com/YOUR_USERNAME/YOUR_FORK.git (fetch)
> origin  https://github.com/YOUR_USERNAME/YOUR_FORK.git (push)
```
```
$ git remote add upstream https://github.com/Aritra8438/GSoC_archive.git
```

```
$ git remote -v
> origin    https://github.com/YOUR_USERNAME/YOUR_FORK.git (fetch)
> origin    https://github.com/YOUR_USERNAME/YOUR_FORK.git (push)
> upstream  https://github.com/Aritra8438/GSoC_archive.git (fetch)
> upstream  https://github.com/Aritra8438/GSoC_archive.git (push)
```
- Before making any changes, sync your origin with upstream 

```
$ git pull upstream main --rebase
``` 


- Make some changes to the project. After that, open a new branch and commit the changes.

```
$ git checkout -b <new_branch>
$ git add .
$ git commit -m "Proposals for <org_name> added"
$ git push origin <new branch>
``` 

- There will be visible change in your repo, click on that and create a new pull request.

Thank you for the contribution.

