# learningGithub
I am learning about git and github &amp; how to use it.
Author-BhanuPratapJha
<div>
git clone githublink : cloning a repository on our local machine.
git status  : displays the state of the code

//List item
ls : lists all the files(non-hidden) of our repository stored inside our local pc.
ls -hidden : also lists the hidden files present inside the repository

//Adding  --> Adds new or changed files in your working directory to the Git Staging area.
git add filename : adds a particular file (new or modified) into our github
git add . : adds all files (new or modifed) into our github.

//Commit --> it is the record of change
git commit -m "some message" : generally try to keep is meaningful

After adding and commiting new changes if we execute command "git status" it will show "Your branch is ahead of 'origin/main' by 1 commit" iska basic mtlb ye hai ki humare local system pe ab hum 1 commit aage ho gye hain as compared to humara github. To change sko github par update karne ke liye we have to execute following command.

//Push --> upload locAL repo to the remote repo
git push origin main
</div>