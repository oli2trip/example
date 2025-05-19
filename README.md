1. Create a Github account(if you don’t have one).
1. Create new Github repository.
1. Create “Task1” folder in the master branch. Create and push ./Task1/README.md file.

![1stcode](/Downloads/Git/example/carbon1.PNG)
![A screenshot of a computer

AI-generated content may be incorrect.](Aspose.Words.d362bd1a-f77f-4951-9e99-e7c679c7c940.001.png)

1. Create a new branch dev. Create and push any test file.
1. Create a new branch %USERNAME-new\_feature.
1. Add ./README.md file to your %USERNAME-new\_feature branch
1. Check your repo with git status command
1. Add .gitignore file to ignore all files whose name begins “.”
1. Commit and push changes to github repo.

mkdir Task\_1

cd Task\_1

git init 

touch task1.md

git add .

git commit -m "add README file"

git branch -M main

git remote add origin main <git\_ripo\_SSH\_Url>

git push -u origin master

git branch dev

git switch dev

touch test\_file.txt

git add test.txt

git commit -m "add test\_file"

git push -u origin dev

git switch -



git switch -c oli2trip-new\_feature

touch README.md 

git status

touch .gitignore

git add .gitignore

git commit -m "add gitignore"

git push -u origin oli2trip-new\_feature

echo "changes" >> README.md

git commit -am "add changes to README"

git reset --hard <commit key>

git log

git switch main

touch log.txt

echo "git log" >> log.txt

git switch dev

git branch -d oli2trip-new\_feature

git push origin -d oli2trip-new\_feature

touch commands.md

git add .

git commit -m "add log and commands file"

git switch main

git pull origin main

git push

git switch dev

git push 


[def]: oli