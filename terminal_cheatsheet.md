# History of the Terminal

Right now we are interacting with the 'shell' of the OS. 
The terminal is built on the UNIX OS, which si the predecessor of most modern day OSs like mac OS etc.
To run an OS it takes up a lot of space and computing power, but using the terminal will take up a lot less space.

## <u>Terminal Commands</u> 

| Command     | Action |
| ----------- | ----------- |
| **pwd**  | stands for print working directory, which tells you where you are in the terminal |
|**~ (tilde)** | demonstrates that we are at home in the directory |
|**ls** |lists all of the things that we have. The bright blue is for folder ad the files or extnesions are in white. This will be our most used command.|
|**ctrl + l OR clear**|clears the screen - it does NOT delete the code on the screen, it just moves the cursor to the top again|
|**ls -l** |is a flag, which shows a detailed list of the folders and files. It will be used on occasion.|
|**ls -a** |shows hidden files that we do not want the average user to modify otherwise they may break vital pieces of code.|
|***Side note:*** the **-l and -a** flags can be combined to give their cumulative effect.|
|**cd + folder_name**| will change the directory to go to the folder that has been stated.|
|***Side note:*** f you type in **cd** by itself, it will take you back to the home directory it does not matter where you are. (This is essentially a get out of jail free card).|
|**cd + D + tab key**| will show you the folder options which start with D. If you keep hitting the tab it will highlight a specific folder for you as you go along. if you press enter on a specific folder it will take you there. will be useful when you have very complicated long folder names.|
|***Side note:*** you can type in **cd + Doc + tab** and it'll go straight to documents, then you can start staying a sub folder too and it'll take you there.|
|***Side note:*** **A ***parent*** folder will only ever be one folder** so you don't have to go straight back to the home directory. So you can do **cd ..** - this will take you to the folder above in the file tree, one level up. cd by itself will take you to the home directory.|
|**mkdir + space + name of folder**| will make a directory of that name|
|**snake formatting**|here we are using underscores because otherwise 3 separate folders will be made for 'my second folder' - one for my, one for second, one for folder. 'my_second_folder' only makes one folder.|
|**touch myfile.txt** |will make a text filed called myfile - most files will work better with an extension such as .txt for a text file.|
|**open + file name**| will open up that file.|
|**open .**| opens up the current directory you are in|
|**mv**|can be used for renaming thing *(of course this can just be done manually in the finder)*|
|**mv -** can also be used for moving| 
|**..** |will move it to the parent folder 
**~/folder name**|will move it to this folder, can use tab to autocomplete too and just move through them with your arrow keys|
|***side note:*** to get the **~** symbol press shift and the key next to z on your keyboard.|

- git status
    - See if code is in staging area to be committed

- git add .
    - add all changes to staging area to be committed

- git commit -m "add commit message"

- git push
    - pushes committed code to repository

- git log
    - show commit history

- git pull
    - pull any new code from repository to local machine

- git branch
    - show list of branches that exist locally

- git init
    - Creates a .git folder

Git Workflow

1. Modify files
2. git status
 - Check which files are not commited
3. Add files to staging area
 - git add [file]
 - OR git add . (means all)
4. git status
 - Check what is in the staging area
5. Commit the files in staging area and add commit message
 - git commit -m "Add desciptive message about file changes"
6. git status
 - Should say "nothing to commit"
7. Git log
 - Shows commit history
When ready, push commits to GitHub
1. git push 
- OR 
1. git push origin main (if working with other branches)
 - Push work to GitHub repository
2. Git status
 - Should say “Your branch is up to date with ‘origin/main’. nothing to commit, working tree clean”
3. Reload repository on GitHub to show the changes.