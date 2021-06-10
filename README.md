# python-package-template
Directory structure and setup files for standard simple python package. As per https://packaging.python.org/tutorials/packaging-projects/
Press Use template button to create a new repostory  
Clone to local system    
Edit requirements.txt to suit project  
```
$ python -m venv env-name
```
```
$ source env-name/Scripts/activate
```
or Bin instead of Scripts on Linux  
```
$ python -m pip install --upgrade pip
```
```
$ python -m pip install e .
````  
```
$ python -m pip install -r requirements.txt
```
Change the package folder name to project name 

Edit .travis.yml to reflect new folder name python version etc.  

Create .env file if needed and make sure it is in gitignore  

Create .pypirc file for logging into PyPi and make sure it is in gitignore  

Start writing tests and files!
