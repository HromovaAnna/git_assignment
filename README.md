

# Git Assignment - <HromovaAnna>

a. What is an issue?
An issue on GitHub is a tool used for tracking tasks, enhancements, bugs, and other requests related to a project. Issues allow team members and contributors to discuss and manage the work that needs to be done within the repository.

b. What is a pull request?
A pull request is a feature in GitHub that allows developers to notify others about changes they've pushed to a branch in a repository. It provides a platform for discussing proposed changes, reviewing code, and collaborating on feature enhancements or bug fixes before merging them into the main codebase.

c. Describe the steps to open a pull request?
1. Navigate to your repository on GitHub.
2. Click on the "Pull requests" tab.
3. Click the "New pull request" button.
4. Choose the branch with the changes you want to merge and the branch you want to merge into.
5. Review the changes to ensure they are correct.
6. Click "Create pull request".
7. Add a descriptive title and summary for your pull request.
8. Click "Create pull request" to submit it for review.


d. Describe the steps to add a collaborator to a repository (share write permissions)
1. Go to the repository on GitHub.
2. Click on the "Settings" tab.
3. In the left sidebar, select "Collaborators".
4. Under the "Collaborators" section, click the "Add people" button.
5. Enter the GitHub username or email of the person you want to add.
6. Click "Add <username>" to this repository.
7. Select the appropriate permission level.
8. Click "Save" to confirm.

 e. What is the difference between git and GitHub?
Git is a version control system used locally to manage and track changes in source code or files, enabling multiple developers to work on a project simultaneously. GitHub, on the other hand, is a cloud-based platform that hosts Git repositories, adding collaboration tools such as pull requests, issue tracking, and web interfaces for managing repositories.

 f. What does git diff do?
`git diff` is a command that shows the differences between changes in your working directory and what is staged for commit, or between any two commits or branches. It is useful for reviewing changes before committing them to the repository.

 g. What is the main branch?
The `main` branch is the default primary branch in a Git repository. It usually contains the production-ready code and is where the final merged changes are stored. In most workflows, the `main` branch represents the current working version of the project.

 h. Besides our initial commit if it is a new repository, should we directly push our changes directly into the main branch?
No, it's generally not recommended to push changes directly to the `main` branch after the initial commit. Instead, you should create a new branch for each feature or bug fix, make your changes there, and then create a pull request to merge those changes into the `main` branch. This helps to keep the `main` branch stable and ensures that code is reviewed before it becomes part of the main codebase.