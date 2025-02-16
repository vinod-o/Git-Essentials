𝐆𝐢𝐭 𝐞𝐬𝐬𝐞𝐧𝐭𝐢𝐚𝐥𝐬

𝐠𝐢𝐭 𝐢𝐧𝐢𝐭:
git init command is used to initialize a new git repository in a directory. It creates a hidden .git folder , which contains all necessary files for version control.

syntax: git init

𝐠𝐢𝐭 𝐜𝐨𝐧𝐟𝐢𝐠:
This command is used to configure various aspects of git, including information, preferences, and repository settings.

    git config --global user.name “your-name”
    
    git config --global user.email “your-email”
    
    git config --list
    
    
𝐠𝐢𝐭 𝐜𝐥𝐨𝐧𝐞:
The git clone command allows you to create a local copy of remote repository. It downloads the entire repository , including all branches and commit history.

git clone repository URL 

𝐠𝐢𝐭 𝐬𝐭𝐚𝐭𝐮𝐬:
git status is a command used in git to show the state of the working directory and the staging area. It helps you see which changes are staged for commit, which changes are staged for commit, which files are modified but not staged, and if there are any untracked files.

git status

𝐠𝐢𝐭 𝐚𝐝𝐝:
The git add command is used to add files to the staging area, preparing them for the next commit. You can specify individual files or use wildcards to add multiple files.

git add myfile.txt

git add *.txt

git add .

𝐠𝐢𝐭 𝐜𝐨𝐦𝐦𝐢𝐭:
The git commit commands creates a new commit, saving the changes made to the files in the staging area. It’s essential to provide a commit message to document the changes.

git commit -m “ msg”

𝐠𝐢𝐭 𝐩𝐮𝐬𝐡:
The git push command is used to upload local commits to a remote repository. It updates the remote repository with your latest changes.

git push origin main

𝐠𝐢𝐭 𝐩𝐮𝐥𝐥:
The git pull command fetches the latest changes from a remote repository and automatically merges them with your local branch. It’s commonly used to update your local repository with the latest changes.

git pull origin main

𝐠𝐢𝐭 𝐛𝐫𝐚𝐧𝐜𝐡:
The git branch command allows you to manage branches within a Git repository . It helps you create , delete, or list branches.

git branch branch-name

𝐠𝐢𝐭 𝐜𝐡𝐞𝐜𝐤𝐨𝐮𝐭:
The git checkout command is used to switch between branches or restore files to a previous state.

git checkout branch-name

𝐠𝐢𝐭 𝐦𝐞𝐫𝐠𝐞:
The git merge command combines changes from branches. It integrates the changes made in one branch into another.

git merge branch-name

𝐠𝐢𝐭 𝐟𝐞𝐭𝐜𝐡:
git fetch is a command that retrieves the latest changes from a remote repository without merging them into you local branch. It allows you to check for updates before applying them.

git fetch

𝐠𝐢𝐭 𝐭𝐚𝐠:
This command is used to create , list, delete, or verify tags. Tags are used to mark specific points in the history. They are typically used to indicate stable versions of software.

git tag v1.0.0

𝐠𝐢𝐭 𝐚𝐥𝐢𝐚𝐬:
git aliases like shortcuts or nicknames for longer git commands. It lets you create shorter, easier-to-remember names of the commands.

git config --global alias.ci commit

git config --global alias.br branch

𝐠𝐢𝐭 𝐥𝐨𝐠:
git log is used to view the commit history of a git repository. It displays a list of commits.

git log 

𝐠𝐢𝐭 𝐬𝐡𝐨𝐰:
git show is used to display detailed information about a specific commit, including its changes, metadata, and diff.

git show

git show commit-hash

𝐠𝐢𝐭 𝐬𝐭𝐚𝐬𝐡:
git stash is used to temporarily save changes that are not yet committed, allowing you to work on something else without losing progress. It stores the modifications in a stack-like structure and lets you reapply them later.

git stash

git stash apply ( apply the latest stash)

git stash pop (apply and remove the latest stash)

𝐠𝐢𝐭 𝐫𝐞𝐯𝐞𝐫𝐭:
git revert command is an undo operation that is carried out if we make any mistakes in the commit. revert is a safer option when working with other developers, as it’s preservers the commit history and doesn’t affect others work.

git revert commit-hash

𝐠𝐢𝐭 𝐫𝐞𝐬𝐞𝐭:
It is used to move the HEAD pointer to a specific commit, It modifies the commit history by adjusting the HEAD pointer, the commit history is deleted, it is not safer option when working with multiple developers.

git reset commit-hash

𝐠𝐢𝐭 𝐫𝐞𝐛𝐚𝐬𝐞:
git rebase is used to change the base of a branch by applying commits from another branch on top of it. It’s commonly used to integrate changes from one branch into another while maintaining a clean and linear history.

git rebase main

𝐠𝐢𝐭 𝐫𝐞𝐟𝐥𝐨𝐠:
Reference logs, or “ref logs”, record when the tips of branches and other references were updated in the local repository. Reflogs are useful in various Git commands, to specify the old value of a reference.

git reflog

 





































