# Git Assignment - ibraassi

a. What is an issue?
An issue is an item that can be created in a repository to plan, discuss and track ideas, feedback, tasks, or bugs for work on GitHub. It can be used to track work, give or receive feedback, collaborate on ideas or tasks, and efficiently communicate with others.

b. What is a pull request?
A pull request is a proposal to merge a set of changes from one branch into another. It displays the differences between the content in the source branch and the content in the target branch. Collaborators can review and discuss the proposed set of changes before they integrate the changes into the main codebase.

c. How do I open up a pull request?
In the Branch menu on the main page of the repository, choose the branch that contains the commits. Click Compare & pull request to create a pull request for the associated branch. Use the base branch dropdown menu to select the branch to merge the changes into, then use the compare branch dropdown menu to choose the topic branch in which the changes were made. Type a title and description then click Create Pull Request.

d. Give me a step by step guide on how to add someone to your repository.
On the main page of the repository under the repository name, click Settings. In the Access section of the sidebar, click Collaborators then click Add people. In the search field, start typing the name of the person, then click a name in the list of matches. Click Add NAME to REPOSITORY, and they will receive an email inviting them to the repository.

e. What is the difference between git and GitHub?
Git is a version control software tool that developers install locally on their personal computers. It is a distributed version control system suitable for tracking modifications in source code in software development. GitHub is an online SaaS service built to run Git in the cloud. It is a web-based Git repository hosting service with cloud-based storage that offers all the distributed version control and source code management functionality of Git.

f. What does git diff do?
git diff is a Git command that outputs the changes between Git data sources such as commits, branches, files, etc. It helps see, compare, and understand changes.

g. What is the main branch?
main is the default name that GitHub gives to the default branch in a new repository. The default branch is the first branch in a new repository and is the branch that GitHub displays when anyone visits a repository. It is the initial branch that Git checks out locally when someone clones a repository, and it is the base branch for new pull requests and code commits unless otherwise specified.

h. Besides our initial commit if it is a new repository, should we directly push our changes directly into the main branch?
No, it is not good practice to push changes directly into the main branch. Changes should be committed and pushed to a separate branch. A pull request can then me made with the main branch as the base branch and the branch in which the changes were made as the compare branch. Collaborators can review and discuss the changes before they merge them into the main branch.
