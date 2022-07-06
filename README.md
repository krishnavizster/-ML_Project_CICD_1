# -ML_Project_CICD_1
Machine Learning Project Pipeline 



#create a new machine learning project environment
conda create -p mlenv python==3.7 -y
#to activate evn 
conda activate mlenv/
#To install requirements.txt fiel 
pip install -r requirements.txt 
#To add file 
git add .
git status 
git log
git commit 

#to send version /chnages 
git push origin main
#to check remote url

"git remote -v
git push origin main 
#Git Documentation 

Heroku Id: krishnavizster@gmail.com

Heroku API key = 221c99cd-5fed-44c1-81f1-fabd704e9e44
Heroku App name=mlcicdp

#to intasll ipynb kurnel 
-----
pip install ipykernel 
----

Software and account Requirement.
Github Account
Heroku Account
VS Code IDE
GIT cli
GIT Documentation
Creating conda environment

conda create -p venv python==3.7 -y
conda activate venv/
OR

conda activate venv
pip install -r requirements.txt
To Add files to git

git add .
OR

git add <file_name>
Note: To ignore file or folder from git we can write name of file/folder in .gitignore file

To check the git status

git status
To check all version maintained by git

git log
To create version/commit all changes by git

git commit -m "message"
To send version/changes to github

git push origin main
To check remote url

git remote -v
To setup CI/CD pipeline in heroku we need 3 information

HEROKU_EMAIL = anishyadav7045075175@gmail.com
HEROKU_API_KEY = <>
HEROKU_APP_NAME = ml-regression-app
BUILD DOCKER IMAGE

docker build -t <image_name>:<tagname> .
Note: Image name for docker must be lowercase

To list docker image

docker images
Run docker image

docker run -p 5000:5000 -e PORT=5000 f8c749e73678
To check running container in docker

docker ps
Tos stop docker conatiner

docker stop <container_id>
python setup.py install
Install ipykernel

pip install ipykernel
Data Drift: When your datset stats gets change we call it as data drift

Write a function to get training file path from artifact dir

Software and account Requirement.
Github Account
Heroku Account
VS Code IDE
GIT cli
GIT Documentation
Creating conda environment


Creating conda environment

conda create -p venv python==3.7 -y
conda activate venv/
OR

conda activate venv
pip install -r requirements.txt
To Add files to git

git add .
OR

git add <file_name>
Note: To ignore file or folder from git we can write name of file/folder in .gitignore file

To check the git status

git status
To check all version maintained by git

git log
To create version/commit all changes by git

git commit -m "message"
To send version/changes to github

git push origin main
To check remote url

git remote -v
To setup CI/CD pipeline in heroku we need 3 information

HEROKU_EMAIL = anishyadav7045075175@gmail.com
HEROKU_API_KEY = <>
HEROKU_APP_NAME = ml-regression-app
BUILD DOCKER IMAGE

docker build -t <image_name>:<tagname> .
Note: Image name for docker must be lowercase

To list docker image

docker images
Run docker image

docker run -p 5000:5000 -e PORT=5000 f8c749e73678
To check running container in docker

docker ps
Tos stop docker conatiner

docker stop <container_id>
python setup.py install
Install ipykernel

pip install ipykernel
Data Drift: When your datset stats gets change we call it as data drift

Write a function to get training file path from artifact dir

os.getcwd()
os.chdir(("here copy the path got from os.getcwd command only upto project folder not notebook folder on this path")
os.list(".") #ro check the list folders and files 

config_file_path = os.path.join("config","config.yml")
#to chek fiel path 
config_file_path 

#to check only this file path available or not 
os.path.exists(config_file_path)

#Hot to read yaml files  
config_info=None
with open(config_file_path,'rb') as yaml_file:

      config_info=yaml.safe_load(yaml_file)
      

#now open 
cofig_info 
