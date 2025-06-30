# initial commit
# second commit
# third Commit
# manualcommit
# rebase Commit
git add <filename> - staging 
 
 ##Command	                                  ##Affects                           ## Use Case	                             ## What It Does

git restore --staged or --source	       Staging area	                  Unstage a file you accidentally added	       Moves changes from staging back to working directory

git reset	                              Staging area (default)	        Unstage commits or files	            Can unstage or move HEAD to a previous commit

git rm --cached <file>	                    Index (staging only)	      Stop tracking a file (e.g., .env)        	Removes file from Git but keeps it in the working dir

git revert <commit>                     	Commit history	            Undo a commit without rewriting history     	Creates a new commit that reverses changes of a prior one


git diff -> shows unstaged changes 
git diff --name-only -> shows unstaged changes file names only
git diff --cached -> shows staged changes
git diff --cached --name-only  -> shows staged changes file names only

