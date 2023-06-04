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


---using SSH 
ssh-keygen
cat sshKEYFILE.pub
copy and paste in github ssh key setting save it

ssh -T git@github.com

to resolve authentication error

eval "$( ssh -agent -s)"

ssh-add sshKEYFILE

hit again "ssh -T git@github.com"  the git and github cconnection using ssh


now you can push the changes using ssh 

git push -u origin development



