Task and Assignment.

What is Version Control? 

Version control is a system that tracks changes to files over time, allowing you to revisit and compare different versions of a project. It helps multiple people collaborate on a project, keeping track of who made changes, when, and why. Git is a popular version control system widely used in software development.

Explain the Difference between git and github?
Git is a distributed version control system that allows you to track changes in your source code during software development. It operates locally on your computer.
GitHub, on the other hand, is a web-based platform that provides hosting for software development using Git. It offers additional features like collaboration tools, issue tracking, and pull requests. GitHub acts as a remote repository where you can store your Git repositories and collaborate with others.

List 3 other github alternatives?
GitLab: Similar to GitHub, GitLab is a web-based platform for Git repository management. It offers features for collaboration, CI/CD (Continuous Integration/Continuous Deployment), and more. GitLab can be self-hosted or used as a cloud-based service.

Bitbucket: Owned by Atlassian, Bitbucket is another alternative offering Git repository hosting. It supports both Git and Mercurial version control systems. Bitbucket provides features like pull requests, pipelines, and integration with other Atlassian tools.

SourceForge: An older platform, SourceForge provides version control services (including Git) and a collaborative environment for software development. It includes features such as bug tracking, forums, and project management tools.

Explain the difference between git fetch and git pull?

 git fetch:
Fetches changes from a remote repository to your local repository.
It doesn't automatically merge those changes into your working branch; instead, it updates your remote-tracking branches.
Useful to see what changes are available on the remote without merging them into your local branch immediately.

 While
 
 git push:
Sends your committed changes to a remote repository.
It updates the remote repository with the changes from your local branch.
It's typically used to share your work with others or update a shared branch on the remote repository.

Explain in simple terms git rebase and the command for it?

In simple terms, git rebase is a Git command used to integrate changes from one branch into another. It allows you to combine a series of commits into a single, linear history. 
The command for it is : git rebase <target-branch>

Explain in simple terms git cherry-pick and the command for it?

In simple terms, git cherry-pick is a Git command that lets you copy a specific commit from one branch and apply it to another branch. It's like choosing a single commit and adding it to another branch.
The command for it is : git cherry-pick <commit-hash>
