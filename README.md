# PLPBasicGitAssignment
This is my my plp git assignment

## STEPS AND COMMANDS
Create the online repository at github.com
Create your local directory and open it in terminal
Create your hello.txt file using the following command:
 `touch hello.txt`
Open your hello.txt file using:
`vi hello.txt`
Insert your words and press:
 `Ctrl+C`
 followed by:
 `:wq` to exit vim
### PULLING AND MERGING YOUR ONLINE REPOSITORY
Pull your online repositoty using ssh link:
 `git pull git@github.com:user/repo.git`. 
The SSH link can be found on the Code section on your online repository.
Add your local files using:
 `git add .`
Insert your commit message using:
`git commit -m "message" `
If you run into a merging problem, try adding the following line of code to yyour terminal:
`git pull origin branchname --allow-unrelated-histories`
Remember to replace branchname with your branch name, "Main or Master"

## PUSHING TO GIT

Add the remote url destination by using the following code: 
`git remote add origin git@github.com:user/repo.git`

Finally push to git using:
`git push -u origin branchname(main or master)`

### AUTHENTICATION PROBLEM
If you run into authentication problems, it means you haven't set your ssh key. Kindly refer to the following link on setting up your ssh key 
https://www.theodinproject.com/lessons/foundations-setting-up-git 
