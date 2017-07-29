//////////////////////////////////////////////
 GITHUB GUIDE (b/c Emily is forever clueless)
//////////////////////////////////////////////

GET COPY OF A REPOSITORY ON GITHUB:
git clone (url)

PUSH CHANGES:
git add (filename)
git commit -m "This is a message detailing the changes I made"
git push origin branch

ADD ALL FILES FROM DIRECTORY:
git add * OR git add .

FORCE REMOVE LOCAL FILES & CHECKOUT TO ANOTHER BRANCH:
git checkout -f another-branch

UNDO LOCAL CHANGES:
git checkout -- <bad filename> (overwrites local changes, restoring to old code)

RETRIEVE LATEST COMMITS IN BRANCH: *always do this before committing changes*
git pull

SEE WHAT FILES HAVE BEEN CHANGED LOCALLY:
git status

WHEN CAN'T MERGE, JUST STASH:
git stash

FINALLY, WHAT IS ORIGIN:
git checkout origin/branch_name = working in local repository
git checkout branch_name = on actual branch in git