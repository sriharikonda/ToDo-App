# Todo :

This service is written in NodeJS, Hence need to install NodeJS in the system.


To Update and Install nodejs run below commands :

```
# apt update
# apt install npm -y
# useradd -m -s /bin/bash todoapp
# cd /home/todoapp/
```
Lets clone the code from github repository.

```
# git clone https://github.com/zelar-soft-todoapp/todo.git
# cd todo/
# npm install
```
NOTE: Configure below environment variable

```
# export REDIS_PORT=6379
# export REDIS_HOST=172.31.59.255
```
Finally start the Todo Module once to effect the changes by the below cammand.

```
# npm start
```

