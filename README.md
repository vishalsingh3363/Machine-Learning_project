# Machine_Learning_Project-1
This is first machine learning project
 
#software and account requirements
1. Github Account
2. Heroku Account
3. VS code IDE
4. GIT cli


crating conda environment
```
conda create -p venv python==3.7 -y
```


activating virtual enviornment
```
conda activate venv/
```


to add requirements.txt file
```
pip install -r requirements.txt
```


to add file to git
```
git add .
```

or

```
git add <file name>
```


to check the git status
```
git status
```

to check all version maintained by git
```
git log
```


to create version/commit all changes by git
```
git commit -m "message"
```

to send version/changes to github
```
git push origin main
```

to check remote url
```
git remote -v
```


to setup CI/CD pipeline in heroku we need 3 information

1. HEROKU_EMAIL = tan.vishalsingh@gmail.com
2. HEROKU_API_KEY = <>
3. HEROKU_APP_NAME = ml-regression-vis

build docker image
```
docker build -t <image_name>:<tagname>
```
 > Note: Image name for docker must be in lowercase



 to list docker image
 ```
 docker images
 ```


 to run docker image
 ```
 docker run -p 5000:5000 -e PORT=5000 <image id>
 ```


 to check running container in docker
 ```
 docker ps
 ```


 to stop docker container
 ```
 docker stop <container_id>
 ```


```
python setup.py
```


install ipynb kernel
'''
pip install ipykernel
```



 
