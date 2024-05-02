### Git from Starting

Agenda
1) Git 
2) Git Workflow

Why need github?

1) old code lost
2) backups issue
3) not proper sharing

We can't even think like that?

how do we handle these kind of scenarios?

Version Control System -> 
what is vcs?
benefits
1) stores history of changes made to each and every file.

1) why / what / when / who of a change

you did that you commit

lets revart that changes?

just imagine, ever be practically is possible?

centralize the repository?

makes collaboration easy

who changes did this?

every thing is tracked 

who uses vcs?

1) developers, testing, devops team, manager, product manager.. corporate level.. can we use at individual level?

own personal project? 

daily sitting, and do some changes

just commit, and push code, evently, you 

features of changes,

revert a feature, complete control of 

go back to your changes..

its become easy for you..

just helps in better..

vcs is individual level, and enterprise

Git is most common version control system..


Open Source version control system.. inherit at any level, lets you do that own version control system..

Github
Gitlab
BitBucket

git is a approach
tools, built up inheritantly, like github, gitlab, bitbucket.

only the command will change.

are the similar, but command will the change, but concept is same..

github - stores git repository online..

github - limited local system it 

why do we need, 

github - it stores git repository online..

github will do?

just local system itself.

basically is publically available tool, where is store git repository..

what is git repository> 
something like a project

equavalent is project

one common sandbox = one complete single, project is git repository


multiple git repository means multiple git project in online..

a git repo can have any type of files, code, text, images, jar files.

what is local and remote repository

local repository is qual to currently on our computer..

remote repository move to complete folder github account, this remote folder is known as remote repository..


uploading folder on google drive?

you are the person to push your own,


who controls git, you are the person the control github controls..


local repo - folder, files
repository - repreesnt a folder..

clone few thing, have you noticed?

anybody?

what was happening is, we have store some starter, own personal account..

today we going to git byte..


let invest our time..

what is git bytes??

crio have own private repository, own unique repository..

understand these concepts.. do let me know as..

1) mkdir -p ~/workspace/byte

- mkdir - means to create directory
- -p - means represent as a parent, if not have then create by yourself.
- ~/ - means home directory
- /workspace/bytes - created directory

cd - change directory 


2) git clone url_link (ssh link)

you appear to have cloned an empty repository..

meanwhile ..

own unique repository..

crio is created empty repository.. it is an empty repository..

how to clone git repository..

3) git remote -v

remote - means online repository
-v -> means verbose means in details information regarding git repository..


which command can be used to create local version of the repository at url?

answer: git clone url_link

which of the following is the tru regarding the repository you downloaded you from gitlab using the git clone.. command?

answer: have folder .git


you should be able do it again..


why do we need commit.

answer: all your changes, all the code merge..

we have to we first..

. dots stand for adding to all files..
4) git add .
5) git commit -m "working"

-m means message..

git commit -m "working"

gitlab.crio.do

what you cloning empty repository..

first add then commit,

without add can't be commit..

then push that

git push -u origin master



### RECAP - HOW TO USE GITHUB

1) create repository online.
2) git clone new_repo_url
3) git add .
4) git commit -m "working"
5) git push origin main

these are important command when we use a new github repository..

this is how is basic level of,

gitlab - for enterprise of level
github - individual level

### Branches uses?

what the uses of Branches
make the changes in master branch then files is changing again..

here is the correct approach..

when changes done by anybody then create messi..

what is this is master..

we have concept of branches..

master protected branch..
nobody is allowed to push into the branch.

except the administrator.

by the administrator only push the code..

most simplest term..

common repository?

Master - > bug free / running on production mode.

Other Branches -> running on bug, with testing mode..

**** how to create new branch

how do we need to create

git checkout -b "branch_name"

create and switch to that branch

checkout means checking out of specific commits.

-b means create branch. (create and switch it)

what is meaning of pushing the code..
### Pushing the Code
Local Repository to Online Repository

### Pulling the Code
Online Repository to Local Repository

Command is 

git pull origin main






basically branch means, to add a code in different branch, and push, after checking, then admin can merge other branch code to main branch -> once verify and checkng whole code, then add to the main branch, after all code checking..



is an making sense..

default branches is main and master..

where to protect our branch.?


### Where to check conflicts?

using commands

1) git rebase master

then resolve all the things..
after all done conflicts.

2) git rebase --continue

3) git rebase main

4) git merge main


are you able to imagine now, all developers, do that 

git branch same thing..

git add .

whenever the time, do watch the recordings.

skip theoratical parts..



cloning or downloading a repo

git clone url_link

when you redo, from your commits.

you can write the few commands..

git reset --soft HEAD~1

undo one of my commits.

if i write HEAD~2 then two commits.

Commiting or making a git checkpoint

Steps Involved

1) Add files to be considered for the next commit.

-- Command:  git add file_name

2) Make a commit
-- Command: git commit -m "Commit_message"

3) to view commit history, we can use

Git log


Its a pointing to a Branch


i can the checking complete history..


if you want to check in one single line then you can use..

git log --oneline

### Uploading new commits to remote.

Git command: git push origin_name Head
head can be: master, main, what is the name of the branch

### Downloading updates from remote..

one of the your colleagues added their updates to the remote repo. how would 

Command Can be: Git pull origin branch_name


does git clone and git pull have the same functionality?

### Pull: takes code from branch
### Clone: takes code from overall repository

### in case of fire
git commit
git push
git out


From Local to Remote (github)

Working directory (git add )
stagging area (git commit)
localREpo (git push) to remote

From Repository to local

Just do that
Git pull origin main..

what is staging area?

after commiting files, or project that is a staging area?


Untracked?

Tracked Files..

### GitHub Recap

git status

just changes in files that would be not in staging area. mark is red

> git add .

after changes then staged. mark is green

changes need to be commited.

> git commit -m "working message"

Git Commands Recap

1) How to check status of the local git repo? > git status
2) how to get details on all past commits? > git log


3) how to add all file changes to the staging area for the next commit? > git add .

4) How to check the current branch name? > git status, or git branch (complete branches)

Tools like github / github making the functionality > Public / Private


### Why making updates directly to the master branch isn't recommended?

no review / not working systematically ways..

so thats the reason..
not allowed to commit into the master code..

utter chaos, or utter mess, never ever be handle..

1) possiblity of buggy code
2) pulled by other developer
3) released to customer if auto deployement is set up from master branch.


early access program, beta program, insider program, limited set of users..

### Branches in git
1) allows to create a copy of the current master branch and work on it separately
2) avoid needing to add commit to the master immidietly

3) commits in the new branch can be merged to the master branch once your code is ready and tested.

4) can create a branch for
>> different featues
>> different teams
>> different product releases (e.g. Feb release)

should we create a branch for each developer working on a project?
NO.

### Proper Better Git Workflow
1) create a new branch for the new release
2) move to the new branch
3) make changes and commit them
4) push changes to the new branches
5) get it reviewed for any issues
>> functional or clean code.
6) merge branch to master.



Activity is
1) create a new branch and make 2 commit there
2) move back to the master branch and verify these commits are not yet aded to the master branch (use git log)
3) merge the changes from the new branch to the master branch
4) verify the new commits are now added to the master branch.

### When can the conflict happen?

same line of a file changed in both blue and green branches.


### Git Trivia : HEAD
refer to the most recent commit in the current branch





























