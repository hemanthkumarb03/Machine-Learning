# Machine-Learning
1. [Git Documentation](https://git-scm.com/docs/gittutorial)


### Anaconda commands
Creating conda env 
```
conda create -p <env name> python==3.9 -y
```
```
conda activate hemanth/
```
```
conda info --evns
```
```
pip install -r requirements.txt
```
### GIt commands

To Add files to git
```
git add .
```
OR
```
git add <file name>
```
> Note : To ignore file or folder from git we can write name of file/folder in .gitignore file

To check Git Status
```
git status
```
to check all the versions maintained by git
```
git log
```
To create version/commit all changes by git
```
git commit -m <"message">
```
to send version changes to git
```
git push origin <branch main
>
```
to check remote url
```
git remote -v
```

To setup CI/CD pipeline in heroku we need below information

1. HEROKU_MAIL = <mail id>
2. HEROKU_API_KEY = <api key>
3. HEROKU_APP_NAME = <app name>

BUILD DOCKER IMAGE
```
docker build -t <image_name>:<tagname> .
```
> Note: Image name for docker must be lower case


To List docker images:
```
docker images
```

To run docker Image
```
docker run -p <port>:<port> -e PORT= <port> <image id>
docker run -p 5000:5000 -e PORT=5000 faa9e602a4cf
```

To check running container in docker
```
docker ps
```

To stop any container
```
docker stop <conatiner id>
