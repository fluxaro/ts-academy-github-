This is what I want us to do. 
Now you create a repo and have a file called *contributors.md* inside of the repo.
- we will then fork the repo so it will create a copy of the repo on our account 
- thwn we're going to clone the forked repo to our machines - Go to your GitHub account, opened the forked repo, click on the code button, then on SSH tab and then copy the URL. 
- now let's cd into the repo
- we then create a branch using the git switch command right so we can work on a separate branch 
- now we can open the contributor.md file with either nano or vim, add your name to it and save it. 
- now still in the project directory if we run git status you'll see there are changes. You can then add those changes by using git add contributors.md
- now we commit those changes using the git commit command. E.g git commit -m "Add your-name to Contributors list" please replace your-name with ur name
- now we can push changes using git push. git push -u origin your-branch-name
- now we can go to our GitHub account and click on compare & pull request, submit the pull request
