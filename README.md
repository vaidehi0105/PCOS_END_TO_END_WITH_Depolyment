# PCOS DETECTION WITH END TO END DEPLOYMENT 

### I will explain how to do modular coding and use various functions and mlops tools such as DVC pipeline 

## Steps include:

###  Step 1 :Setting up Template.py

1. Create a template.py file : this file will be used to create a project structure ( will create all the files and folders on the project)

### Step 2: Setting up requirement.txt

1. Create a requirement.txt file : this file will be used to list down all the libraries and requirements for this project

### Step 3: Setting up Setup.py 

1. This will download all the libraries present in the requirements.txt file.

2. Run the file using python -r requirements.txt


### Step 4: Now its type for logger 

1. write the logger coder into  __init.py__ file in src folder. Logger is used to log messages for a specific application component.

### Step 5: We have to write code in utils folder. 

1. Utils are those functions which we use frequently in code. 
2. For example : we have .yaml file in every directory to call that everytime we dont want to write the code every time.

3. Create a file called common.py in the utils folder , here you will write all the utility related functionalities.

4. The common.py folder will consist of common functionalities such as :
    1. Reading yaml file
    2. Creating directories
    3. Saving json file
    4. Load json file
    5. save binary file
    6. Load binary file
    7. decode image
    8. encode image

why used ConfigBox?
Because config box is used for additional handling of string manipulation generally found in config files.

### Step 6: Project workflow 

1. Update config.yaml file
2. Update secrets.yaml (optional)
3. update params.yaml
4. update the entity
5. update the configuration manager in src config
6. Update the components
7. Update the pipeline
8. Update main.py
9. Update the dvc.file
    