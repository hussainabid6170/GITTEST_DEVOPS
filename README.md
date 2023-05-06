# GITTEST_DEVOPS
devops testing for testing from git bash into git hub : below are the steps

mkdir ~/Hello-World

cd ~/Hello-World

git init


echo "ADD README CONTENT" > README.md
git add README.md


git commit -m 'first commit'

git remote add origin https://github.com/username/Hello-World.git

git push origin master



git remote set-url origin https_link_to_repository

git push -u origin master
