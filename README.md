# This is my learning note at Alt School Africa.

NB: I use windows OS

Steps to cloning this repo:


1. Create a new folder on your local machine and cd into the folder.

For example; 

<br>
mkdir AltSchoolClone
<br>

<br>
cd AlSchoolClone
<br>

2. While in the newly created folder, folk and git clone the repo into the folder.

<br>
git clone https://github.com/YourGitHubUsername/Alt_school_note
<br>

cd  into the cloned folder;

'''
cd Alt_school_note 
'''

3. Add an upstream, which links to the original GitHub repo;

<br>
git remote add upstream https://github.com/BrodaOJ56/Alt_school_note
<br>


4. Create and move into a new branch (preferably using your name or GitHub username for this repo):


<br>
git checkout -b YourBranchName
<br>


5 Open the folder in your code editor, while in your code editor, activate the virtual environment and install all dependencies (requirements txt file)

<br>
cd .venv
<br>

<br>
cd scripts
<br>

<br>
.//activate
<br>


Once the virtual environment is activated, install requirements txt file.

<br>
pip install requirements.txt
<br>


6. When you're done for the session:

Make changes and stage your changes by adding them:

<br>
git add . or git add file.name
<br>


Then commit the staged changes:

<br>
git commit -m 'message here'
<br>


Push the changes to your branch:

<br>
git push origin YourBranchName
<br>

This is when you'll usually create a pull request on GitHub.


To fetch the latest, do 

<br>
git pull upstream main
<br>
