# Edfoal.github.io 🌍

### Setup Instructions ⬇

1. Install [Hugo](https://gohugo.io/getting-started/installing/) 

2. Check if it installed properly or not. By running below command on terminal. 

``` 
$. hugo version

output : Hugo Static Site Generator v0.68.3/extended linux/amd64 BuildDate: 2020-03-25T06:15:45Z
```

3. First fork this repo by clicking Fork icon 🍴 on top right corner & then clone your repo using command

```
$. git clone https://github.com/your_github_username/Edfoal.github.io.git
or
$. git clone git@github.com:your_github_username/Edfoal.github.io.git
```
4. Change directory & add upstream repository URL
```
$. cd Edfoal.github.io/
$. git remote add upstream https://github.com/Edfoal/Edfoal.github.io.git
or
$.git remote add upstream git@github.com:Edfoal/Edfoal.github.io.git
```
5. Always Pull recent changes from upstream repository before doing any work then checkout different branch other than main
```
$. git pull upstream main
$. git checkout -b branch_name
```
6. Run site on your local env, By running below command
```
$. hugo serve
```
7. Navigate to [localhost:1313](localhost:1313) through your browser.

8. Make changes and stage those changes with this command.
```
$. git add .
```
9. Write commit message, Follow this [convention](https://www.conventionalcommits.org/en/v1.0.0/). 
```
git commit -m"commit_message_here"
```
10. Push those changes to your Fork Repo, and [Create Pull Request](https://www.atlassian.com/git/tutorials/making-a-pull-request).
```
$. git push origin your_branch_name
```

11. Sit back & Relax and wait for maintainers for rewiewing your [PR](https://www.atlassian.com/git/tutorials/making-a-pull-request).
