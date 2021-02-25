.md means mark down file

Commit is make changing and then commit
Branch is one version of a code
BRANCH:
    git checkout -b new
    git add .
    git commit -m "first commit on new branch"
    git checkout master
    git merge master (for merging new branch to master)
    
Working with Remote:
    git push -u origin master
setup username, useremail and password:
    git config --global user.name "Ahsan"

git pull origin master
git push

PULL:
    git pull is one of many commands that claim the responsibility of 'syncing' remote content. 
    The git remote command is used to specify what remote endpoints the syncing commands will 
    operate on.
PUSH:
    The git push command is used to upload content to a remote repository.