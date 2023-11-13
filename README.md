# Git-Commands
List of git commands: https://www.digitalocean.com/community/tutorials/how-to-push-an-existing-project-to-github

```
git init
git add -A
git commit -m 'Added my project'
git remote add origin git@github.com:sammy/my-new-project.git
git push -u -f origin main
```

1. Initialised repo
2. -A = All files
3. -m = message
4. git remote add origin is instructing git to add the URL of the default remote server for this repo
5. -u (or --set-upstream) flag sets the remote origin as the upstream reference. This allows you to later perform git push and git pull commands without having to specify an origin since we always want GitHub in this case.
6. -f (or --force) flag stands for force.
   


