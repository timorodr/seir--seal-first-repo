# My First Readme

I;m going to use this readme to document what we've learned about github!

- Creating the Repo
    1. create an empty folder `mkdir <name>`
    2. cd into that folder `cd <name`
    3. initialized the repo `git init`

- Committing your work
    1. add files to staging `git add.`
    2. commit `git commit -m "message"`

- Push work to gitbub.com
    1. Create a new repor on github.com
    2. copy the url https/ssh for the repo
    3. add the remote repo to your local repo ` git remote add origin <url>`
    4. push up the commits `git push origin main` or `git push origin master`

- misc commands
    1. see the status of your repo `git status`
    2. see what branch you are on `git branch`
    3. see previous commits `git log`
    4. see list of remotes `git remote -v`
    5. remove the origin remote so you can readd it `git remote rm origin`