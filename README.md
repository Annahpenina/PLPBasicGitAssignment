first creat a repository on github as instructed called " PLPBasicGitAssignment "
then head to Git in your pc and create a local repositrory called " PLPBasicGitAssignment "
then type comands "cd c:/ " to choose a path for your repo.
"mkdir PLPBasicGitAssignment" to make directory
"cd PLPBasicGitAssignment"
then "git init" to initialize Git repository in the chosen path
Link my local repository to the GitHub repository i created 
with "git remote add origin https://github.com/Annahpenina/PLPBasicGitAssignment.git"
go to your local machine in your file explora, look for the folder you created using Git on the chosen path.
create a txt document file in tha folder and save.
head back to git to type command "ls" to list all files in that folder/repository
the hello.txt file you created is listed.
type command "vim hello.txt" in order to add text in the text file, hello.txt you created
thus press "i" to edit , write your message then press "esc" on your keyboard as well as ":wq" to save exit editing yor file.
command "git add hello.txt" for git to stage changes made
with git commiit -m "add your desired message" command you can commit the changes you made
and "git push -u origin main" to push your local repository to your github repository of the changes made.
then head to github to confirm that the hello.txt file is visible and commit message is also visible.
