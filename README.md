# learn-git-demo
Learning Git and Git Hub
<p>Learning git From Apna College.</p>
<p>clone command : git clone file-link</p>
<p>status command : git status</p>
<p> Once the code is edited in the vs code we need to perform two task so the new changes may get added and commited. (1) add (2) commit</p>
<p>
untracked : new files that git doesn't yet track 
modified : changed 
staged : file is ready to be commited 
unmodified : unchanged
</p>
<p> Add : adds new or changed files in your working directory to the git staging area. 
git add file name, also to add all changes write git add .</p>
<p>commit : it is the record of change 
git commit -m "some message" 
</p>
<p>To show those changes in git hub we use push : git push origin main </p>
<p> 
1. cd file name - used to go in sub folder or file
2. pwd - used to check in which file or folder we are
3. cd ..   - is used to come out from file or folder</p>
<p> init - used to creat a new git repo
git init</p>
<p> make new repo on cs code : mkdir fileName</p>
<p> 
to add local repo to remote : git remote add origin link 
to verify remote : git remote -v
to check branch : git branch
to rename branch : git branch -M newName
if we're working on same repo for long time , so instead writing alway git push origin main we simply give command give push -u  origin main. later only type git push
</p>
<p> 
git checkout branchName: used to go to another branch
git checkout -b newBranchName : used to create new branch
git branch -d branchName : used to delete branch
git diff x(branchName) : comparing y branch to x branch 
git merge x(branchName) : merging two branches i.e. y to x in github
git pull origin main : remote yanii github waale changes vs code main bhi dikhenge
# undoing changes
1. staged changes , maane add kia pr commit baki hain : git reset fileName
2. commited change, maane commit kia pr psh karna baki hain : git reset HEAD~1
3. many commit : git reset commitHash
</p>