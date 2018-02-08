# This is a header and my first repo!!!

This is the README.md file in my first repo. There are many like it but this one is mine. 
I *think* I got the header right

## Common git Commands
* "git init" Initializes a repo
* "git --config user.name" Sets username for the repo
* "git --config user.email" 
* "git status" Checks the status of the repo 
* "git add --all ." Add all files from current directory down to repo 
* "git commit" Commit to the repo all changes from previous add
* "git push" Push changes 
* "git clone" Clone an existing repo 

Jay here, working on the first pull request:
A few topics we covered in todays call:
## Topics briefly mentioned:
*- Linus Torvalds
*- FOSS
*- Linux
*- git
*- vi
*- markdown (https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
*- The command line (BASH Shell)


## Pull Request Update
*First thing I did was "Fork" the repo from inside github. That created my own version of the repo in my account.
* Cloning my forked version repo: 
```
$ git clone https://github.com/JayFJones/FirstRepo.git JayFirstRepo
Cloning into 'JayFirstRepo'...
remote: Counting objects: 9, done.
remote: Compressing objects: 100% (5/5), done.
remote: Total 9 (delta 2), reused 8 (delta 1), pack-reused 0
Unpacking objects: 100% (9/9), done.
```
* Adding and commiting these changes:
```
$ git add --all .
$ git commit -m "Pull request instruction update."
```

* Pushing the branch to the repo:
```
$ git push origin jay_pull_request
```
After that we will figure out what it takes for Justin to accept the pull request.




