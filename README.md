# dsr-test-b32
Check this first: \
https://github.com/Iskriyana/dsr-teaching-setup
## Pycharm

## Git 
`git status` \
This checks the status of files in your folder \
\
`git add.` \
adds all the changes for the subsequent commit \
\
`git commit -m 'a message for the commit` \
commiting, with message for keeping track of what the commit is about \
\
`git push origin main `\
this will push from origin to main

## Anaconda environment
For Each new project, it is good to create a new anaconda environment
``conda create -n dsr-setup python=3.8`` \
Here we set up with `conda` a new environment `-n` using python version `3.8` \
``conda activate dsr-setup`` will activate the new environment

## pip install
create a `requirement.txt` file and write the following lines in it: \
`numpy==1.19.2` \
`pandas==1.1.3` \
`seaborn==0.11.0` \
`scikit-learn==0.23.2`

After activating a given environment, the packages from the requirement file can be installed as followed: \
``pip install -r requirements.txt``
