# How to save a project to github

Download the ```.gitignore``` file contained in this repository and place it in your directory, which will allow you not to save useless files and therefore reduce upload and download time

Create your own repository on GitHub

Open Windows powershell
Navigate inside your project directory
type:
-	```git init``` to start a git repository locally
-	```git add .``` to stage all the files
- ```git branch -M main``` to make sure the name of your local branch is main
- ```git commit -m "[put a comment here that explains your commit]"``` It is standard practice to write 'first commit' for your first commit
- ```git remote add origin [link to your repo]``` links your local and remote repo
- ```git push -u origin main``` pushes staged changes from your local repo to the remote

Anytime you want to push to the remote type ```git push -u origin main```
Anytime you want to pull from remote type ```git pull origin main``` 

##Troubleshooting

If everything is failing, you can check ```git status``` where you should see the branch you are own, which should be main, and all the changes to be committed
