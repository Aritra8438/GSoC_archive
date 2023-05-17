<p align="center">
    <img src="https://github.com/Rishabh04-02/The-Beginners-Guide-to-Google-Summer-of-Code-GSoC/blob/master/gsoclogo.svg">    
</p>
<p align="center"><b>An open-source project that aims to gather proposals and experiences of GSoC across the years</b></p>


## Contribution:

If you have previously applied for GSoC, you might help build this repo by contributing the proposals you submitted or by sharing your experience in GSoC.

Sometimes, great proposals are rejected due to the,
- submission of an even better proposal,
- Limited slots given by GSoC to the orgs.
 
So, even if your proposals are rejected, please contribute them as well.

**If your proposal has been accepted, try to link the project announcement to the pull request.**

## Aim:

If you are a GSoC candidate, this repository may help you write the proposals based on the organizations you are applying for.


## Folder Structure

```
|-GSoC Year
    |-Organisation Name
        |-Proposals
            |-Accepted
                |-Project-topic_user-name.pdf
            |-Rejected
        |-experience
```

Please follow the naming conventions.


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


## Commits

- Write clear meaningful git commit messages (Do read [this](http://chris.beams.io/posts/git-commit/)).

## Organizations with atleast one proposal
- [x] Mathesar
- [x] KDE
- [x] CircuitVerse
- [x] CERN

