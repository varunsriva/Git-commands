# Git-commands
Git commands assingment-1

STAGE & SNAPSHOT
1. git status – Displays the state of working directory and the staged snapshot
2. git add “file name”– Moves changes from the working directory to the staging area.
3. git reset “file name”- unstaging a file while retaining changes in working directory.
4. git diff – difference of what has been changed but not staged.
5. git diff –staged - difference of what has been staged but not yet committed.
6. git commit -m ‘a message/changes in the file’” – commit your staged content as a new commit snapshot.

SETUP
7. git config --global user.name “[firstname lastname]” – set a name that is identifiable for reviewing version history.
8. git config --global user.email “[valid-email]” – set an email address that will be associated with each history maker.

BRANCH & MERGE
9. git branch – list your branches, a * appears next to currently active branch.
10. git branch [branch-name] – creates a new branch at the current commit.
11. git checkout – switch to another branch and check it out into your working directory.
12. git merge [branch] – merge the specified branch’s history into the current one.

SETUP & INIT
13. git init – intialize an existing directory as a git repository.
14. git clone [url] – creates copy of existing git repository from remote to local.

SHARE & UPDATE
15. git push [alias] [branch] – transmit local branch commits to the remote repository branch. 
16. git pull – fetch and merge any commits from the tracking remote branch.