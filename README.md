## If this is helpful give it a star. :star:

# Git/Github-with-VS-code :sunglasses:

## INSTALLATION
 
### STEP 1: Check whether the Git is installed on your laptop/pc or not

#### To check the installation --open "command prompt" and type [ git --version].

If the version is present 

   - then proceed with step-2
   
else

  - Search git-scm.com/downloads on google or click on the [link](https://git-scm.com/downloads)

then download git for windows.

### INITIALIZATION OF REPOSITORY
### STEP 2: Make a Github account and Make a repository on your GitHub account.
To use Github in vs code you have to login from vs code and install the extension [Git Pull requests and Issues](https://marketplace.visualstudio.com/items?itemName=GitHub.vscode-pull-request-github).

Download [github desktop](https://desktop.github.com/) for windows 

Login into GitHub desktop and clone the repository you made and then click on **open with VS code.** 
- Complete the steps of authorization.

-> Now after logging in, you can clone the repository you made directly in vs code.

-> If you have opened the cloned repository make a folder and files to check whether you are getting the untracked option or not. If it is not there then your folder is not initialized. so first initialized it.

-> If you are getting the untracked option commit it and type a message according to your commit and then push it to origin main by writing [git push origin main] in the terminal.

#### To initialize a repository create a directory/folder first. (NOTE: Do not use your home directory to install or initialize git, it will mess up your computer).

1. For initializing you need to be on that folder where you want to initialize it. 
2. You can use the command git init to intialize the repository.


### -------- If you want to use Github directly from VS CODE ---------

- Make a new folder on VS code (you will see there is nothing in it).
- Type [git init] to initialize the repository. 
- Open the Terminal and make a file and if you want to use GUI 
    - **STEPS
:** Type (a) open .  (b) touch first.txt 
It will create your file.
- To commit your file you can directly click on the source control icon or you can type [git commit].
- You can now push it in main by writing [git push origin main]

***Till now we have learned how to create a file and initialize a repository***
- To delete a file, type **rm first.txt**

We have done a lot of operations till now so let's check the status.
 
**Type: git status** in termial


## SOME IMPORTANT POINTS 

If you want to remove a complete folder & dis-commit it. 

**Use command** :- rm -rf .git
(It will remove the git repository and every single file).

### To initialize git with command line
 1. First check the version of git software installed type **[git --version]**
 2. To initialize type **[git inti]**, you will see an empty repository will be initialized.

#### NOTE: While creating any new file you will see *U* at the end -- it means the file is "untracked" and has not been pushed in your repository yet. 

Similarly, **A** represents: Added and **M** represents Modified.

For more, you can follow these tutorials
1. [Workshop play list](https://www.youtube.com/playlist?list=PLO_Y0rsm7b3aubpJhA6Td7af9Vjk0mDAm).
2. [Complete Git and GitHub Tutorial](https://www.youtube.com/watch?v=apGV9Kg7ics).
