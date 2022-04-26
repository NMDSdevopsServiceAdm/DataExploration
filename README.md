# Data Exploration

This repo has been set up as a place for exploration notebooks to exist. This is not a repo of production ready code and should not be treated as such. This repo should never store and data, although notebooks may contain summarised views, descriptions and graphics.  

The code in this repo exists primarily in jupyter notebooks. 

## Create a virtual environment
When working on any project, it is best practice to encapsulate the work within a virtual environment. The idea behind this is that each developer is able to set up an environment on their device that is identical to that of their colleagues. This project will use `venv` as it is the most straight forward for the work that this repo will cover.

### Create virtual environment
```
python -m venv .venv
```

### Start virtual environment
``` 
source .venv/bin/activate
```

### Stop virtual environment
```
deactivate
```

## Install required packages
Install all packages and libraries required to run the notebooks in this repo. 

``` 
pip install -r requirements.txt
```

### Add new packages to requirements file
If, during you work, you require additional packages or libraries then please add them to the requirements file using the following command. 

```
pip freeze > requirements.txt
```

## Data 

To maintain data security, the`Data` folder and its contents has been added to the `.gitignore` file. This means that anything stored within this folder will NOT be uploaded to git. In order to run these notebooks it is likely that they will require data in some form. Along with each notebook, please provide a description of how to attain this data, what format it is required to be in and how to name it. Place follow the instructions found within the notebook you are working on and ensure that the data you require is in the correct directory. 