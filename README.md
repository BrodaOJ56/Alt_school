# This is my learning note at Alt School Africa.

NB: I use windows OS

Steps to cloning this repo:


1. Create a new folder on your local machine and cd into the folder.

For example; 

`
mkdir AltSchoolClone
`

`
cd AlSchoolClone
`

2. While in the newly created folder, folk and git clone the repo into the folder.

`
git clone https://github.com/YourGitHubUsername/Alt_school_note
`

cd  into the cloned folder;

`
cd Alt_school_note 
`

3. Add an upstream, which links to the original GitHub repo;

`
git remote add upstream https://github.com/BrodaOJ56/Alt_school_note
`


4. Create and move into a new branch (preferably using your name or GitHub username for this repo):


`
git checkout -b YourBranchName
`


5 Open the folder in your code editor, while in your code editor, activate the virtual environment and install all dependencies (requirements txt file)

`
cd .venv
`

`
cd scripts
`

`
.//activate
`


Once the virtual environment is activated, install requirements txt file.

`
pip install requirements.txt
`


6. When you're done for the session:

Make changes and stage your changes by adding them:

`
git add . or git add file.name
`


Then commit the staged changes:

`
git commit -m 'message here'
`


Push the changes to your branch:

`
git push origin YourBranchName
`

This is when you'll usually create a pull request on GitHub.


To fetch the latest, do 

`
git pull upstream main
`
