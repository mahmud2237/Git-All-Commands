

git --version => check the current git version

cd => to see the current repo folder location

cd .. => back from the current folder

cd [current folders folderName here] => it will go to the folder

cd ["folder location or address"] => Instantly go the folder

mkdir [New_foldername] => make a new directory folder here

git init => the command used to create a new repository

rm -rf [foldername] => it will delete or remove the folder [-rf is a flag] 

touch [new_filename] => create a new file 

rm [Filename_want_to_delete] => delete or remove the file

N:B: in windows powershell the touch command will not recognizes so use this command instead to crate a new file:

echo $null >> [new_filename] => it will create a new file in windows powershell

cat [file_name] => to see inside the file

nano [file_name] => to edit the file [In Nano command we can use: (E)dit, (R)ecover, (Q)uit, (A)bort]

git rm -f [file_name] => forcefully removes or delete the file from the working directory [-f is a flag]

git rm --cached [file_name] => to ignore the file or untrack the file by git

git commit => First time it will ask "Tell me who you are?" Then give the details of your git account:

git config --global user.email "Your email address"
git config --global user.name "Your github profile username"

git --help => to see all git command

git log => to see the commit logs

git checkout [branch_name] => to switch branch

git branch -a => to see all git branches

git branch -d [branch_name] => to delete selected branch 

git revert [commit_log] => to reset or revert the commit file

.gitignore => create a filetype .gitignore and put the filetype name inside it which filetype want to ignore

git rm -r --cached . => to remove all untracked catched if .gitignore not working than.

git restore --staged [file_name] => that will untrack the track file





*** What is HEAD? => The currently selected commit called HEAD.

*** What does the command 'git add .' do? => Add all files to the staging area.

*** Which command used to create a new repository? => git init.

*** How do you add and checkout a branch in Git?? => git checkout -b <newbranch_Name>

*** What is a branch? => A chain of commits that doesn't interfere with other branches.

***

***

***

***

***

***

***