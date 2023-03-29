# prework-study-guide
Study guide for U of U bootcamp pre work

1. WE made sure that our main branch was synced up to the cloud (git pull)
    - if any errors, use git restore . to undo any file changes
    -alternatively, we can use git revert < commit hash> to go back in time

2. If our main branch is synced, use git checkout -b <new branch name> to switch to a new branch 
    -Work on our code, make any updates, and do a git push
    -git add <files we want to add>      -----  "." or "-A" to add all files
    -I can do a git status to check what is staged to be committed
    -git commit -m "<Write a detailed message>"
    -git push
        -- you must copy the set upstream code git suggests to link your branch up

3. If we push up, we must go to the cloud and create a pull request,
    -If approved, be sure to merge it and delete the branch on the cloud

4. On your local computer, git checkout main
    -Perform a git pull to make sure you are synced to the cloud
    -Delete the branch locally
    -Before touching your main (you can use git status), repeat step 1# Prework-Study-Guide
