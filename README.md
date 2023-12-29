End to End Machine Learning project
Steps:
1. Create a folder where you want to do the project
2. Open Anaconda Prompt
3. Open vs code from the folder
4. Create a conda python environment and activate
   conda create --name venv python
   conda activate venv
5. Initialize a git repo
6. Create a github repo
7. update git
8. Create a gitignore file from github repo and perform git pull for synchronisation
9. Mention the filenames which you dont want to upload in github (ex: venv)
10. Create setup.py file
11. create requirements.txt file
12. Upload the CSV file (inside notebook folder)
12. Create a components, pipeline folder inside src
13. Create required python files like data_ingestion, data_transformation, model_trainer inside components 
and product_pipeline, train_pipeline 
14. Then Perform EDA and model training (folders located inside notebook)
15. Then Python src/components/data_ingestion.py is executed
15. After all the modelling and training part, app.py file is created and the webpage for the prediction is created using Flask
16. Then the webpage is run in local host. 
    python app.py
    Run and enjoy the Program. :)