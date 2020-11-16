Git Essential:

    *https://git-scm.com/

    git init -> initalize a git repository

    git add <files> -> take snapshot of the contents of files

    git commit -> permanently store the contents of the index in the repository
        -a -> automatically notive any modified files, add them to the index and commit

    git diff -> show any changes but not yet added to the index
        --cached -> see what is about to be committed

    git status -> brief summary

    git log -> view the history of yours changes
        -p -> see complete diffs at each step
        --stat --sumary -> get a feel of each step
    
    git branch <branchname> -> create a new branch 
    
    git branch -> get a list of all existing branches
        -d <branchname> -> delete the branch, ensures that the changes in <branchname> branch are already in the current branch
        -D <branchname> -> just delete the branch

    git switch <branchname> -> switch branch

    git merge <branchname> -> merge the changes made in two differents branches

    git clone <path<repositoryname>> <newdirectoyname> -> creates a new directory <newdirectoryname> containing a clone of <repositoryyname>

    git pull <path<repositoryname>> <branchname> -> merges the changes from the <branchname> in <repositorychanges> into the current branch in current directory - the pull command performs two operations: it fetches then merges

    git fetch <path<repositoryname>> <branchname> -> peek the <repositoryname> without merging first

    gitt remote add -> define a remote repository

    git config --get remote.origin.url -> location of remote repository

    git show -> see the details about this commit

    git tag <tagname> -> give commits names of your own




       



