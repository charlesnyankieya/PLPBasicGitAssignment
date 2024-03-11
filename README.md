# PLPBasicGitAssignment
This is my my plp git assignment

## STEPS AND COMMANDS
1. Create the online repository at github.com
2. Create your local directory and open it in terminal
3. Create your hello.txt file using the following command:
 `touch hello.txt`
4. Open your hello.txt file using:
`vi hello.txt`
5. Insert your words and press:
 `Ctrl+C`
 followed by:
 `:wq` to exit vim
### PULLING AND MERGING YOUR ONLINE REPOSITORY
6. Pull your online repositoty using ssh link:
 `git pull git@github.com:user/repo.git`. 
The SSH link can be found on the Code section on your online repository.
7. Add your local files using:
 `git add .`
8. Insert your commit message using:
`git commit -m "message" `
9. If you run into a merging problem, try adding the following line of code to your terminal:
`git pull origin branchname --allow-unrelated-histories`
10. Remember to replace branchname with your branch name, "Main or Master"

## PUSHING TO GIT

11. Add the remote url destination by using the following code: 
`git remote add origin git@github.com:user/repo.git`

12. Finally push to git using:
`git push -u origin branchname(main or master)`

### AUTHENTICATION PROBLEM
13. If you run into authentication problems, it means you haven't set your SSH key. Kindly refer to the following link on setting up your ssh key: 
https://www.theodinproject.com/lessons/foundations-setting-up-git
14. You can always know your git status using:
`git status`

### THANK YOU! 
