# CQRE_Linux

* sudo add-apt-repository ppa:git-core/ppa
* sudo apt-get update
* sudo apt-get install git-core
* git version
* git config --global user.name "SuBin0"
* git config --global user.email "ksb4150@naver.com"
* git config --global push.dafault "simple"
* mkdir ~/linuxrepo1.git
* cd linuxrepo1.git
* mkdir homeworks
* cd homeworks
* git init
* git status
* vi helloworld.c
* git add helloworld.c
* git commit -m "sentence output 'Hello world!' used 'printf function'"
* git remote add origin https://github.com/SuBin0/CQRE_Linux.git
* git push origin master
* git pull origin master
* git fetch --all
* git reset --hard origin/master
* git commit --amend
* git commit -m "cange 'Hello world!' to 'Hello Linux'"
* git push origin master
