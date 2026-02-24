# Applied-Data-Science-1
Week 5 exercise 

Practicing the version control system (GIT) and making use of version control system in the machine as well as making commits and editing files 
The work flow as follows:
  Creating a Repository (Repo)  -Command Line: git init
  Command Line: git init  -Cloning creates a local copy of a remote repository on your computer.
                Command Line: git clone [URL]
  Committing Changes :A commit is a record of what changes you have made since the last commit.
                git status  # to see the list of changed files
                git add <whatever files>  # to stage those files for commiting
                # additionally as appropriate
                git rm <files>  # deleting files from git
                git mv <files>  # moving/renaming files
                git commit -m "Your commit message"  # to place the commit
                # alternatively
                git commit -a -m "Your commit message"  # staging all modified files and placing commit

  Pushing Changes:Pushing means uploading your committed changes to a remote repository.
                git remote -v  # see the remote sources like origin and upstream
                git push origin [branch-name]  # push the staged commit(s)
                # you may need, if there are multiple branches that you want to edit
                git push --set-upstream <origin/upstream> [branch-name]
                # often, just
                git push  # needed

  Pulling Changes:Pulling is the act of downloading changes from the remote repository to your local repository.
                Command Line: git pull origin [branch-name] or just git pull
