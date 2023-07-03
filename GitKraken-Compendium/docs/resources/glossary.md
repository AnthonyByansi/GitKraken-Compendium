# GitKraken Glossary

This glossary provides definitions for key terms and concepts used in GitKraken. Familiarizing yourself with these terms will help you navigate GitKraken's features and functionalities more effectively. 📚🔍

## Terms and Definitions

- **Repository**: A repository is a storage space where your project's files and version history are stored. It can be local or remote.

- **Branch**: A branch is a separate line of development within a repository. It allows you to work on new features or bug fixes without affecting the main codebase.

  - **Create a branch**: To create a new branch, use the command `git branch <branch-name>`. Example: `git branch feature-branch`.

  - **Switch to a branch**: To switch to an existing branch, use the command `git checkout <branch-name>`. Example: `git checkout feature-branch`.

- **Commit**: A commit represents a snapshot of your code at a specific point in time. It is a way to save changes to the repository.

  - **Stage changes**: To stage changes for a commit, use the command `git add <file-name>` or `git add .` to stage all changes.

  - **Commit changes**: To commit changes, use the command `git commit -m "Commit message"`. Example: `git commit -m "Added feature XYZ"`.

- **Merge**: Merging combines changes from one branch into another. It allows you to incorporate the changes made in a feature branch back into the main branch.

  - **Merge branches**: To merge a branch into another branch, use the command `git merge <branch-name>`. Example: `git merge feature-branch`.

- **Pull Request**: A pull request is a mechanism for submitting contributions to a repository. It allows you to propose changes and initiate a discussion before merging them.

- **Remote**: A remote is a repository hosted on a server, such as GitHub or GitLab, which enables collaboration and code sharing.

- **Fetch**: Fetching retrieves the latest changes from a remote repository without merging them into your local branch.

  - **Fetch changes**: To fetch changes from a remote repository, use the command `git fetch`. Example: `git fetch origin`.

- **Push**: Pushing sends your local commits to a remote repository, updating its branch with your changes.

  - **Push changes**: To push changes to a remote repository, use the command `git push <remote> <branch-name>`. Example: `git push origin feature-branch`.

- **Pull**: Pulling fetches changes from a remote repository and automatically merges them into your current branch.

  - **Pull changes**: To pull changes from a remote repository, use the command `git pull <remote> <branch-name>`. Example: `git pull origin main`.

## Conclusion

This glossary provides an overview of important GitKraken terms and associated commands. Refer to this resource whenever you come across unfamiliar terms or need clarification on specific concepts. Understanding these terms will empower you to navigate GitKraken with confidence. Happy coding! 💻🎉
