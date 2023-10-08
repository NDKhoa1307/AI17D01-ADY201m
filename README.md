To use this repo, first use this in your terminal (mind your current working directory):

    git clone "https://github.com/NDKhoa1307/AI17D01-ADY201m.git"

After that, make sure you have virtualenv installed by using this in your terminal (mind your current working directory):

    pip install virtualenv

After virtualenv has been installed, create a new virtual environment with the name of your choice, activate it and then install all the required packages
by using this in your terminal (mind your current working directory):
    
    ./{name of your virtual environment}/Scripts/activate
    pip install -r ./requirements.txt

After all has been done, you should see this in your terminal:
    (env) PS {current working directory}

If not, good luck fixing the bug :D



If you have already created a virtual environment before, make sure you use the correct kernel when executing .ipynb files, you can be certain of this by 
checking out the kernel option on the top-right corner of your .ipynb file, a prompt will pop up, choose Python environments -> {the name of your virtual environment}

If you cannot find it, your virtual environment might not have been created, then what are you waiting for, shithead ?:D



This repo contains a folder named Components, in which should contains the files related to this project, I would recommend read them all before hitting that run all button,
although it should not have any effects on your computer, being cautious is always the best :D




!! IMPORTANT, AFTER YOU ARE DONE WITH YOU WORK, MAKE SURE TO PUSH IT TO YOUR BRANCH, NOT THE MAIN BRANCH
   WHICH MEANS WHATEVER YOU DO, DO NOT PUT THE WORD MAIN IN YOUR TERMINAL, EVER                         !!

After all of that, init your git folder in your current working directory by using: git init

Next, establish a connection with the git repo by using: git remote add origin "https://github.com/NDKhoa1307/AI17D01-ADY201m.git"

Make sure to be up-to-date by using: git pull origin main
(This is the only time you can put main in your terminal :p)

To create a new branch, if you have not done any work, use: git checkout -b {the name of your branch}
This should create a new branch for you and then switch you to that branch as well 

However, if you have already done a lot of work, use: git branch {the name of your branch}
This only create a new branch so it perfectly fine and you will not lose your work

(Check out this link to know how to name your branch: https://dev.to/varbsan/a-simplified-convention-for-naming-branches-and-commits-in-git-il4)

After that, make sure you have staged all of your modified files by using: git add -A 
(In some occasion, the flag -A could be replace with the files you wish to stage and not all of them)

Staging has completed ? Commit the change by typing: git commit -m {commit message}
(Check out this link to know how to write your commit message: https://www.conventionalcommits.org/en/v1.0.0/)

!! One more thing to mention is that you should make sure your code is up-to-date before pushing, it might not change anything, but sure, it 
can help you avoids a lotttttt of issues in the future

All that is left to do is to push your changes into YOUR BRANCH by using: git push origin {YOUR BRANCH}
