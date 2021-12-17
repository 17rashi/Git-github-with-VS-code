# Git/Github-with-VS-code

## INSTALLATION
 
### STEP 1: Check whether the Git is installed on your laptop/pc or not

#### To check the installation open command prompt and type [ git --version].

if the version is present 
   then proceed with step-2
else
   Search git-scm.com/downloads on google or click on the [link](https://git-scm.com/downloads)

then download git for windows.

## INITIALIZATION OF REPOSITORY
### STEP 2: Make a Github account and Make a repository on your GitHub account. 
To use Github in vs code you have to login from vs code and you can install the extension [Git Pull requests and Issues](https://marketplace.visualstudio.com/items?itemName=GitHub.vscode-pull-request-github).

-> Now after logging in, you can clone the repository you made.
#### To initialize a repository create a directory first. (NOTE: Do not use your home directory to install or initialize git, it will mess up your computer).

1. For initializing you need to be on that folder where you want to initialize it. 


#### -------- If you want to use Github directly from VS CODE ---------

- Make a new folder on VS code (you will see there is nothing in it).
- Open the Terminal and make a file and if you want to use GUI 
    - **STEPS
:** Type (a) open .  (b) touch first.txt 
It will create your file.
- To commit your file you can directly click on the source control icon or you can type git commit.
- You can now push it in main by writing [git push origin main]

***Till now we have learned how to create a file and initialize a repository***
- To delete a file, type **rm first.txt**

We have done a lot of operations till now so let's check the status.
 
**Type: git status** in termial


#### SOME IMPORTANT POINTS 

If you want to remove a complete folder & dis-commit it. 

**Use command** :- rm -rf .git
(It will remove the git repository and every single file).

### To initialize git with command line
 1. First check the version of git software installed type **[git --version]**
 2. To initialize type **[git inti]**, you will see an empty repository will be intialized.

#### NOTE: While creating any new file you will see *U* at the end -- it means the file is "untracked" and has not been pushed in your repository yet. 

Similarly, **A** represents: Added and **M** represents Modified.
