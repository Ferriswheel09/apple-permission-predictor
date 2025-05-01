# apple-permission-predictor
Open-Source Neural Network used for Identifying Apple Privacy Labels

## Getting Started
To use the following data and recreate the results, you must do the following:
1. Unzip data.zip. This will output a data.json file that contains all the apps, the metadata, and the privacy data necessary for the models to train on. 
2. Create the venv environment and install all the requirements. Jump to the venv section for more information
3. Run the json_to_csv python notebook. This will condense the json data to be used in a more formatted way. 
4. Run model1.ipynb and mdoel2.ipynb. This will generate all model training and analysis that was used. 

## Using Venv
This installation process was done on Windows with Git Bash. The requirements.txt is frozen in the root directory of the project. To use, created venv in workspace and install requirements for usage. 
In the root directory of the project, run the following:
```
python3 -m venv venv
source ./venv/Scripts/activate
pip install -r requirements.txt
```     

Running the python notebook on VS Code, make sure that you select the virtual environment as the kernel that is used. 