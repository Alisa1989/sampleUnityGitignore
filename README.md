# How to use GitHub for your Unity projects

## Getting Started - Saving a project to Github

Download the ```.gitignore``` file contained in this repository and place it in your directory, which will allow you not to save useless files and therefore reduce upload and download time

Create your own repository on GitHub

Open Windows PowerShell
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

## Pulling a project on a new device
- open git bash
- navigate to the folder where you will be saving your project using ```ls``` to find where you are and ```cd``` to enter folder
- type ```git init``` - to initialize an empty git repository
- type ```git clone [project link from your github repo]```

## Troubleshooting

If everything is failing, you can check ```git status``` where you should see the branch you are own, which should be main, and all the changes to be committed
