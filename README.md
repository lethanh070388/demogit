git init
git config --global user.name 'ABC'
git config --global user.email 'abc@gmail.com'

git status
git add index.html
git add *.html
git add .

git rm --cached index.html
git rm --cached *.html

git commit -m 'Message content'
git reset --soft HEAD~1

.gitignore

git branch login

git checkout login
git merge login

git branch -d login
