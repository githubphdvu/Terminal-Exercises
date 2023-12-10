## **Part I**
- make directory called first: *mkdir first*
- change directory to first: *cd first*
- create file called person.txt: *touch person.txt*
- change its name to another.txt: *mv person.txt another.txt*
- make copy of another.txt and call it copy.txt: *cp another.txt copy.txt*
- remove copy.txt: *rm copy.txt*
- make copy of first folder and call it second: *cp -r first second*
- delete second folder: *rm -rf second* (recursive deletion(includes subdirectories);force:suppresses error messages and prompts, allowing the command to continue without interruption)

  ## **Part II**
- *man* command lists the manual for a command
- ⌃-D/⌃-B/⌃-U: scroll pages
- ls-la l:flag list more detail; a:flage lists all files/folders including hidden ones(with dot)
- jump between words: *Alt <-/->*
- get to beginning/end: *^ a/e*
- delete a word up to cursor: *^ w*
- delete from beginning up to cursor: *^ u*

- *terminal* just provides an interface to the shell
- *shell* is CLI (command-line interpreter) to interpret commands you enter into terminal 
- *absolute path* is a path that starts from root route and gives the complete location for a file or folder
- *relative path* is a path that starts at current location
- *flags* add additional functionality to command(ex: ls -al, cp -r, rm -rf)
- rm -rf: recursive deletion(includes subdirectories);force:suppresses error messages and prompts, allowing the command to continue without interruption
