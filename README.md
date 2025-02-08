Step1:
We made a folder in the local pc.(Our Computer)
Local repo is not connected with the git.

2:
Now we make local repo(folder) part of the git by 
intializing it as "git init"

3:
We add a file and then connect local repo to remote 
repo using => git add "filename"

4:
Now, we need to commit the files too. using
=> git commit -m "comments"

5:
We upload our modified file from local to github
but we also need another repo(folder) in the github
and we do that by creating a new repo directly in github and copying its link. Then we 
=> git remote add origin "link"

6: 
Now we need to push the data to the cloud(remote) repo and we do it using command like
=> git push origin main
//more like uploading the change to the github repo.

