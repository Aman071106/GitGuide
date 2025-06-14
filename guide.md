Basic setup-watch video
Basic commands
->init,clone,pull,push,fetch,commit,add,reset


git branch
git branch -M newName
git checkout -b branchName  

//
till we have atleast one file/one commit in our repo no branch is created so on git branch we will see empty output

//
git remote add codespaceName https://github.com/Aman071106/GitGuide.git
git remote -v
codespace1      https://github.com/Aman071106/GitGuide.git (fetch)
codespace1      https://github.com/Aman071106/GitGuide.git (push)
codespaceName   https://github.com/Aman071106/GitGuide.git (fetch)
codespaceName   https://github.com/Aman071106/GitGuide.git (push)

rendundant if we have multiple aliases

so remove one

git remote codespaceName



At a particular commit in remote we can tap on the rightmost '<>' icon to explore repo history at that point


We can have different folders in our local connected to remote and make changes through them



git restore --staged filename to undo git add filename  

git reset filename to undo git add filename
