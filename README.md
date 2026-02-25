Stage 1: Basic Setup (Foundation)

1. mkdir ml-project
2. cd ml-project
3. git init
4. echo "" > train.py
5. echo "" > predict.py
6. echo "" > utils.py
7. echo "" > README.md
8. git status

Stage 2: Version Control Workflow (Application)

1. git add train.py utils.py --> To add the files to stage
2. git commit -m "Add training script and utilities" --> Commit the code to ready to move for Github 
3. git remote add origin https://github.com/KG06/ml-project.git --> add the Github link to local
4. git branch -M main --> To setup the branch for commit
5. git push origin main --> Push code to our main branch
