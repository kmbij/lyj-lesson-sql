#README.md
# Initialize Environment
in terminal:
. git --version
. git config --global user.name 'Lin Yi Jie'
. git config --global user.email 'hhh0952354933@gmail.com'
. git init

# Common Used Instruction
. git status
. git log --oneline

# Track File and Folder
create a new README.md file, ctrl + S
. git add [full file name]
. git add *.file_sub_nmae
. git add .
. git commit -m 'message'

# Regular Process
. git add .
. git commit -m 'message'
. git push

# others instruction of modify file
. git reset --soft HEAD~ #回到上一動/canceling cpmmit
. git reset --hard[version.number]
. git diff [version.number] -- [filename]
. git checkout [version.num] -- [filename]
