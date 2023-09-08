# website
Homework Assignment Week 1
NOTES:

1. Version control allows us to track changes made in software projects. This allows creators to “travel back” to previous versions of files and directories without changing the properties and content of the current project. VCS provides a way to securely back up projects and share it with other developers. (2)
2. There have been many VCS but the one that stands out the most is Git. Git is a command-line program and was created by Linus Torvalds (creator of the Linux system) and is very powerful for the few commands that it has. (3)
3. Using -p option together with mkdir creates intermediate directories -> mkdir -p directory1/directory2. directory2 will be within directory1. (7)
4. Using -a together with git add will make all (untracked) files tracked by git. A good practice since most of the time, we want all files to be tracked. (9)
5. Git hub commits should be relatively small and “granular”. Commits should have a simple message that is concise as to what changes/add-ons were made. (11)
6. Commits are identified by a unique hash with numbers and letters. This hash is used by git to retrieve the version associated with it.(11)
7. git diff shows the difference between the last commit and the unstaged changes of the current project version. (12)
8. git log will show the commits made by git commit. (14)
9. GitHub is a site designed to facilitate remote repositories in collaboration with Git. (31)
10. A frequent issue is dealing with files that should not be committed by Git. Such files include passwords, config files that should not be shared with other computers, temporary files, and log files. (60)
11. Git allows us to ignore certain files/directories using a special hidden configuration file known as .gitignore.
12. Adding *~ to the .gitignore file makes Git ignore all temporary Vim files. Adding some_directory/ to .gitignore will cause Git to ignore the entire some_directory (with its files included). (62)
13. Branches are copies of projects within a repository. Branches can be merged with other branches. We use branches to develop and continue working on a project without fully committing to the main/master branch immediately. Branches are helpful when working with other developers. (63)
15. git checkout -b branch_name will create a new branch from the project you are working on and switch to that branch. (63)
16. We can view current branches that exist using git branch. The branch name with * indicates the one you are currently on. (63)
17. git diff branch1 branch2 will show the differences between the two branches. (67)
18. git merge branch_name will merge branch_name to the current branch you are on. (71)
