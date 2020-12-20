…or create a new repository on the command line
echo "# test" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/qendro/test.git
git push -u origin main
                
…or push an existing repository from the command line
git remote add origin https://github.com/qendro/test.git
git branch -M main
git push -u origin main


…or import code from another repository
You can initialize this repository with code from a Subversion, Mercurial, or TFS project.


```bash
git --version
```
git config --global user.name "Your Name"
git config --global user.email "your@email.com"

git init

git status

git add file.js file2.js file3.js
git add .

git commit -m "Commit message"

git log

git checkout <commit-hash>
git checkout master

git branch <new-branch-name>

git checkout <branch-name>

git merge <branch-name>

 Deleting a branch
 git branch -d <branch-name>

