# Consumer_Complaint_AIOPS


Cloning a project from Git Repo:

'''
https://github.com/ProSoumya/Consumer_Complaint_AIOPS.git
'''

To add the files in Staging area :

'''
 git add <filename>
'''

To  commit the file in Git Repo :

'''
git commit -m "Write of your Message about the changes"
'''

Rename branch to Main Branch:

'''
git branch -m main    (Master branch will  be renamed to main)
'''

To check remote branch url

'''
git remote -v
'''
#origin  https://github.com/ProSoumya/Consumer_Complaint_AIOPS.git (fetch)
#origin  https://github.com/ProSoumya/Consumer_Complaint_AIOPS.git (push)

To remove file from staging area:

'''
git rm --cached <file_name>
'''


Push command :

'''
git push origin main
'''
To send changes to  remote branch:

'''
git push <remote_branch_variable> <branchname>
'''


To create an virtual environment in  this folder:

'''
conda create -p venv python=3.7 -y 
'''

To activate the cvirtual environment
'''
conda activate venv/
'''

To ignore the files for Git_repo

'''
touch .gitignore
'''


To create an  Requirements.txt
pip  freeze>requirements.txt

copy CSV file from one folder to data folder

cp "C:\Users\soumy\Downloads\factbook.csv" data\