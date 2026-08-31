# learn-git-demo
Learning Git and Git Hub
<p>Learning git From Apna College.</p>
<p>clone command : git clone file-link</p>
<p>status command : git status</p>
<p> Once the code is edited in the vs code we need to perform two task so the new changes may get added and commited. (1) add (2) commit</p>
<p>
untracked : new files that git doesn't yet track <br>
modified : changed <br>
staged : file is ready to be commited <br>
unmodified : unchanged
</p>
<p> Add : adds new or changed files in your working directory to the git staging area. <br>
git add file name, also to add all changes write git add .</p>
<p>commit : it is the record of change <br>
git commit -m "some message" 
</p>
<p>To show those changes in git hub we use push : git push origin main </p>
<p> 
1. cd file name - used to go in sub folder or file<br>
2. pwd - used to check in which file or folder we are<br>
3. cd ..   - is used to come out from file or folder</p>
<p> init - used to creat a new git repo<br>
git init</p>
<p> make new repo on cs code : mkdir fileName</p>
<p> 
to add local repo to remote : git remote add origin link <br>
to verify remote : git remote -v<br>
to check branch : git branch<br>
to rename branch : git branch -M newName<br>
if we're working on same repo for long time , so instead writing alway git push origin main we simply give command give push -u  origin main. later only type git push
</p>
<p> 
git checkout branchName: used to go to another branch<br>
git checkout -b newBranchName : used to create new branch<br>
git branch -d branchName : used to delete branch<br>
git diff x(branchName) : comparing y branch to x branch <br>
git merge x(branchName) : merging two branches i.e. y to x in github<br>
git pull origin main : remote yanii github waale changes vs code main bhi dikhenge<br>
# undoing changes<br>
1. staged changes , maane add kia pr commit baki hain : git reset fileName<br>
2. commited change, maane commit kia pr psh karna baki hain : git reset HEAD~1<br>
3. many commit : git reset commitHash<br>
</p>