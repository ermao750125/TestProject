







# learningMaterial

…or create a new repository on the command line
echo "# learningMaterials" >> README.md
git init
git add README.md
git commit -m "first commit"

git remote add origin https://github.com/ermao750125/TestProject.git
git push -u origin master

…or push an existing repository from the command line
git remote add origin https://github.com/ermao750125/TestProject.git
git push -u origin master …

or import code from another repository You can initialize this repository with code from a Subversion, Mercurial, or TFS project. ProTip! Use the URL for this page when adding GitHub as a remote.



create eclipse project with Eclipse_ProName;
Then enter into github and create a new project named ProName= Eclipse_ProName and copy its address;
Goto eclipse, open repositories window, there are choices:
      Add an existing local Git repository
      Clone a Git repository
      Create a new local Git repository
click the second "Clone a Git repository" and into "Clone Git Repository window"
enter address of ProName as URL, enter your UserName and Password, then click Next, Next, finish.
you will get your local git project name and its address;
then click java project sign at the top right corner and go back to java project environment in eclipse
click project in package discovery, ->team->Share Project into Configure Git Repository Window
select you local repository address into Repository to set up the relation of the project in eclipse and local repository
then finish.
the eclipse project will into local repo

local repo to remote repo github:
right click eclipse project, ->team->Commit then into a git working environment,
select all in unstaged changes, drag them into Staged Changes, write Commite Message, then click Commit and Push
here is the Push Branch Master window, click Next
then provide your username, password, cilck ok, username, password, cilck ok.
then you can see your project now in remote repository i.e. gitHub.

whenever you make changes, you will repeat the steps from right click eclipse project, ->team->Commit.
  












































































# learningMaterial

…or create a new repository on the command line 
echo "# learningMaterials" >> README.md 
git init 
git add README.md 
git commit -m "first commit" 

git remote add origin https://github.com/ermao750125/TestProject.git
git push -u origin master 

…or push an existing repository from the command line 
git remote add origin https://github.com/ermao750125/TestProject.git 
git push -u origin master …

or import code from another repository You can initialize this repository with code from a Subversion, Mercurial, or TFS project. ProTip! Use the URL for this page when adding GitHub as a remote.

s
