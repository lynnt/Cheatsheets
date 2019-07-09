## Diff
**`git diff`**: diff of unstaged change

**`git diff --stage`**: diff of what is staged that will go to next commit

## Commit
**`git commit -a`**: automatically add tracked files with latest changes and then commit

## Removing files
**`git rm <file_name>`**: remove files from disk and untrack the file

**`git rm --cached <file_name>`**: untrack the file but keep the copy on disk

## Moving files
**`git mv file_from file_to`**: track the renaming of the files and rename the file (equivalent to `mv file_from file_to, git rm file_from, git add file_to`

## Log
**`git log -p -<number of entries>`**: show difference introduced in each commit and optionally limit # of entries starting from the latest

**`git log --stat`**: display abbreviated stats for each commit

**`git log --pretty=<settings>`**: reformat the output of log

**`git log --since/after=<time>`**: list of commits to those made after the specified date (e.g. `git log --since=2.weeks`)

**`git log --until/before=<time>`**: list of commits to those made before the specified date

**`git log --author=<name>`**: filter commits based on specific author

**`git log -S <function_name`**: only show commits adding/removing code matching the string

## Undoing things
**`git commit --amend`**: redo the commit with additional changes if there are changes, else it'd allow changing commit message (e.g. `git commit -m 'intial commit', git add forgetten_file, git commit --amend`)

