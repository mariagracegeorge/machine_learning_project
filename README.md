# machine_learning_project

Software and account requirement

1. Github account
2. Heroku account
3. VS Code IDE
4. GIT cli
5. GIT documentation

Creating conda environment
```
conda create -p venv python==3.7 -y
```
```
conda activate venv/
```
```
pip install -r requirements.txt
```

To Add files to git

```
git add .
```
OR
```
git add <filename>
```

> Note: To ignore file or folder from git we can write name of file/folder in .gitignore file

To check the git status
```
git status
```
To check all version maintained by git
```
git log
```
To create version/commit all changes by git
```
git commit -m "message"
```
To send version/changes to github
```
git push origin main
```
To check remote url
```
git remote -v
```

To setup CI/CD pipeline in heroku we need 3 information

HEROKU_EMAIL = gracemaria.george@gmail.com
HEROKU_API_KEY = HRKU-172480b7-71ce-4852-8508-fb1540641f28
HEROKU_APP_NAME = ml-regression-app01

BUILD DOCKER IMAGE

```
sudo docker build -t <image_name>:<tagname> .
```

> Note: Image name for docker must be in lowercase
>       '.' indicates current folder

To list docker image
```
sudo docker images
```

To run docker image
```
sudo docker run -p 5000:5000 -e PORT=5000 <image_id>
```

To check running container in docker
```
sudo docker ps
```

To stop docker container
```
sudo docker stop <container_id>
```


