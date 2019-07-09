## Diff
`git diff`: diff of unstaged change
`git diff --stage`: diff of what is staged that will go to next commit
## Commit
`git commit -a`: automatically add tracked files with latest changes and then commit
## Removing files
`git rm <file_name>`: remove files from disk and untrack the file
`git rm --cached <file_name>`: untrack the file but keep the copy on disk
## Moving files
`git mv file_from file_to`: track the renaming of the files and rename the file (equivalent to `mv file_from file_to, git rm file_from, git add file_to`
