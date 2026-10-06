# For New Project
1. Git Initilization
   ```
   git init
   ```
2. Add files and folder to git for tracking
   ```
   git add .
   ```
   Note: . is for all files and folder, in place of . we can add file name.
3. After completing: save all codes as some version
   ```
   git commit -m "[Your_commit_message]"
   eg: git commit -m "project initilized"
   ```
4. Optional step: chaning main branch
    Note: default branch is always "master"
    ```
    git branch -M "[your_main_branch_name]"
    ```
5. Add remote repo link or repository url
   ```
   git remote add origin "[your_repository_url]"
   ```
6. Push the recent commited code to remote
   For First Time:
   ```
   git push -u origin "[your_current_branch_name]"
   ```
   Later (if one push is already done using **-u**: `upstream`)
   ```
   git push
   ```

# Extra Commands
7. To check the status of git (vcs)
   ```
   git status
   ```
8. To update the remote repo url
   ```
   git remote set-url origin [your_repo_url]

   To Verify/Display added remote url:
   git remote -v
   ```
9. To config the user.name and user.email:
   ```
   Project Based Config:
   git config user.name [your_github_username]
   git config user.email [your_github_email]

   Global Config:
   git config --global user.name [your_github_username]
   git config --global user.email [your_github_email]

   To Verify/Display Config (Note: enter to view more config and q to exit the opened editor):
   git config --list
   ```

# After Changing on Project
   1. git add .
   2. git commit -m "[your_commit_message]"
   3. git push

# Using Personal Access Token (PAT) on https url:
- https://[PAT]@github.com/[github_username]/[project_name]

- git remote add origin [your_github_url_with_pat]

To Update the remote url:
- git remote set-url origin [your_github_url_with_pat]

