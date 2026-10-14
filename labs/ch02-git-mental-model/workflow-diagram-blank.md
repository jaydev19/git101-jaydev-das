### [ WORKING DIRECTORY ] → [ STAGING AREA ] → [ COMMIT HISTORY ]

#### 5 Key term definations :

- Repository : A project folder whose changes are tracked by Git.It contains files and the git history of committed changes.
- Working Directory : The files we are currentely working on.
- Branch : Branch lets us develop changes independentely and then merge the changes to a single main branch
- Commit : A commit is a saved checkpoint of our staged changes. It is permanent and has saved author , message and timestamp.
- Clone :	Creates a local copy of a remote repository, including its history.

#### Flow from working directory to commit history

- In git first create or modify the files on working directory.

- Then run command git add . or git add file_name , to move the files to the staging area 

- Then use the git commit -m "message" to commit the changes and save the file version with a message and timestamp.

- We can view the commit history using the command git log --oneline

- So,the flow is :

-  [ WORKING DIRECTORY ] (edit/create files) → (git add) -> [ STAGING AREA ] (review the files to commit) -> (git commit) [ COMMIT HISTORY ] (git log --oneline)

#### Example of well written commit message 

> git commit -m "Imputed the missing rows from health_records.csv"

