

### Anaconda Steps - 

1. Open anaconda prompt
2. Create a local Folder
3. Copy the path --> cd in anaconda prompt to the path (D:\)
4. Base environment - 
```
conda create -n <my_env_name> python=3.8.8 -y
```
```
conda activate <my_env_name>
```
```
 jupyter notebook
```

## OR

===========================================================================

### VS Code Steps - 

1. Create a local Folder
2. Create a Repo on github --> Add Readme.md - Select Python - Add a License
3. Open Cmd --> cd into local folder --> git clone github repo
4. Go to repo folder on local machine --> Right click - Git bash Here - code .
5. Vscode will open with the folder as working directory
6. Ctrl+Shift+P --> Select base pythn=3.8.8 interpreter --> Open Terminal
7. Select Cmd or Git ( or powershell)  according to the project
8. Create a new virtual environment

```
conda create -n <my_env_name> python=3.8.8 -y
conda create -n movierm python=3.8.8 -y
```
```
conda info --envs
```
```
conda activate <my_env_name>
conda activate movierm
```
===========================================================================

### Create and Install requirements.txt
```
pip install -r requirements.txt
```

### Setup your Github account
```
git config --global user.name "mustafamadraswala" <your github username>
```
```
git config --global user.email "museychamp@gmail.com" <your github email>
```

### Push all the changes and code to Github -
Add all the files to github - 
```
git add .
```

Check status of your files -
```
git status
```

Commit all the files to github by pushing the fies from local to  thestaging environment -
```
git commit -m "This is my first commit includes requirement.txt and readme.md file"
```

Or do both the steps together -
```
git add . && git commit -m "This is my first commit"
```

Push everything to github -
```
git push origin main
```
=============================================================================
