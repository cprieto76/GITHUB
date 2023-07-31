## PULL REQUEST

#### Creating a pull request in GitHub allows you to propose changes made in your branch to be merged into the main branch (e.g., `main`, `master`). 
Collaborators can review the changes and, if approved, merge them into the main branch.  

Here's a step-by-step guide on how to make a pull request:

1. **Create a New Branch (if not done already):**
   - Before creating a pull request, make sure you have created a branch and made the necessary changes in that branch. If you haven't created a branch yet, follow the steps mentioned in the previous response ("How to create a branch in GitHub") to create and switch to a new branch.

2. **Push Changes to GitHub:**
   - Once you have made changes in your local branch, push those changes to the remote branch on GitHub using the following Git command:
     ```
     git push origin branch-name
     ```
     Replace `branch-name` with the name of your branch.

3. **Navigate to Your Repository:**
   - Go to the GitHub website and log in to your account.
   - Navigate to the repository that contains the branch with your changes.

4. **Click on "Pull Requests" Tab:**
   - In the repository, click on the "Pull Requests" tab near the top of the page. This will take you to the pull requests section.

5. **Click on "New Pull Request" Button:**
   - On the right-hand side, you'll see a green button labeled "New Pull Request." Click on it to create a new pull request.

6. **Select the Branches:**
   - On the "Compare changes" page, you'll see two dropdown menus. The base branch should be the branch into which you want to merge your changes (usually `main` or `master`), and the compare branch should be your newly created branch with the changes.
   - GitHub will automatically detect any differences between the two branches.

7. **Review the Changes:**
   - Review the changes shown on the page to ensure they are as you intended. You can see the added, modified, and deleted files along with the line-by-line changes.

8. **Create the Pull Request:**
   - Once you are satisfied with the changes, click on the "Create pull request" button.
   - Add a title and a detailed description for your pull request. The description should include information about the changes made and any context that might be helpful for reviewers.

9. **Create Pull Request:**
   - Click on "Create pull request" to submit the pull request. GitHub will then show your pull request in the pull request list for the repository.

10. **Collaborator Review and Merge:**
    - Your pull request is now open, and collaborators can review your changes, leave comments, and approve the pull request.
    - Once the pull request is approved, a repository maintainer or someone with merge permissions can merge the changes into the main branch by clicking on the "Merge pull request" button.

Congratulations! You have successfully created a pull request in GitHub, and your proposed changes are ready for review and, eventually, merging into the main branch.
