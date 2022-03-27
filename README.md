How to use go.mod example - greetings module called by hello.
https://go.dev/doc/tutorial/call-module-code  
export GO111MODULE="on"  
go run .

# For branching. E.g modify README.md in branch
Branch update and merge
https://docs.github.com/en/get-started/quickstart/hello_gomod
Add branch called readme-edits.  
git branch readme-edit  
git branch -l  
git checkout readme-edit2  
git status  
vim README.md  
git diff   
git commit .
git push  
https://github.com/decspeed/hello_gomod/ 
new pull request  readme-edit2 had recent pushes 3 minutes ago  [compare and merge]  
git log --all --decorate --oneline --graph  
https://nvie.com/posts/a-successful-git-branching-model/  

27/03/2022: Go tutorial next step
https://go.dev/doc/tutorial/module-conclusion
