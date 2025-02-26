[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/8wgCKhpZ)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=18412014&assignment_repo_type=AssignmentRepo)
# se-day-2-git-and-github
## Explain the fundamental concepts of version control and why GitHub is a popular tool for managing versions of code. How does version control help in maintaining project integrity?
Version control offers a platform for a project to be worked on without making unnecessary changes to the source file. It helps track changes made to a particular program over time. 
This way, every change made by a developer can be traced, tracked, edited and even reversed and this helps maintain the integrity of data. Git hub is a cloud-based platform where developers can store, share and make changes to their repositories. 

## Describe the process of setting up a new repository on GitHub. What are the key steps involved, and what are some of the important decisions you need to make during this process?
To set up a new repository, a github account has to be created. 
Proceed to log on using your email address and password
Head to the dashboard page 
To the top lefthand corner, select new repository 
Fill in the required fields marked with asterisks
The desired repository name should be filled in the "repository name" section
Then proceed to create the repository 
You can choose to download the repository file, to your PC, save in a folder and proceed to import in into Visual Studio code where you can make extra changes to the repository. 
Extra changes can be made to the repository via VS code following the steps below 
git.init (To initalise git)
git add . 
git commit -m "First save of the class" (desired file name")
git remote add orgin (
git clone git clone https://github.com/agu803eh/agu803eh (This creates an alternate branch in a bid not to alter the main)
git push orgin main (This pushes created file to the repository, agu803eh in Github)
git show (ashows details and time of changes made to a repo)

## Discuss the importance of the README file in a GitHub repository. What should be included in a well-written README, and how does it contribute to effective collaboration?

A readme file gives an overview of a given project. It tells the scope of the project, outline specific information or instructions required in/of the project as well asdetailing how to set up/ install the project and what contributions other can make to the project.  

## Compare and contrast the differences between a public repository and a private repository on GitHub. What are the advantages and disadvantages of each, particularly in the context of collaborative projects?
A public repository is one which is visible and accessible to the public while a private repository can only be worked on by the root user or those who have the required right privileges.
A public repository is required for open source projects that are to be shared or amde available to the public, community or globally while a private repo is mainly used for internal projects. 
## Detail the steps involved in making your first commit to a GitHub repository. What are commits, and how do they help in tracking changes and managing different versions of your project?

Commits are used to capture the state of a project agt a point in time. 
Please see below how commits are made and how they help track changes 


To set up a new repository, a github account has to be created. 
Proceed to log on using your email address and password
Head to the dashboard page 
To the top lefthand corner, select new repository 
Fill in the required fields marked with asterisks
The desired repository name should be filled in the "repository name" section
Then proceed to create the repository 
You can choose to download the repository file, to your PC, save in a folder and proceed to import in into Visual Studio code where you can make extra changes to the repository. 
Extra changes can be made to the repository via VS code following the steps below 
git.init (To initalise git)
git add . 
git commit -m "First save of the class" (desired file name")
git remote add orgin (
git clone git clone https://github.com/agu803eh/agu803eh (This creates an alternate branch in a bid not to alter the main)
git push orgin main (This pushes created file to the repository, agu803eh in Github)
git show (ashows details and time of changes made to a repo)

## How does branching work in Git, and why is it an important feature for collaborative development on GitHub? Discuss the process of creating, using, and merging branches in a typical workflow.
Branching helps developers make edits to a given code without affacting the main file. Its function is to create an alternate, parallel version of the original code, allowing you to work on it without tempering with the main file. A branch can also be created from an exisitng branch. 

git branch new_feature (to create a new branch)
git checkout new_feature (used to switch branches or move between branches)
git merge new_feature (used to merge branch back to the main when the updates are deemed perfect)

## Explore the role of pull requests in the GitHub workflow. How do they facilitate code review and collaboration, and what are the typical steps involved in creating and merging a pull request?
 A pull request in the Github worflow is a mechanism that allows for changes made in a branch bhy a developer to be reviewed by other team members before it is merged with the main code. It allows for verification and validation to enusre completedness and correctness before merging. 

 To commit 
 git commit add origin https://github.com/Powerlearnproject/se-assignment-day-2-git-and-github-agu803eh/edit/main/README.md
 
 Merge: Creates a merge commit to combine branches.

Example: git checkout main && git merge feature-branch

## Discuss the concept of "forking" a repository on GitHub. How does forking differ from cloning, and what are some scenarios where forking would be particularly useful?
Forking a repo involves making a copy of someone else repository to your own. This is usually for collaborative purposes. 
while cloning a repository requires making a copy of that repository on git hub onto hyour local machine. 

## Examine the importance of issues and project boards on GitHub. How can they be used to track bugs, manage tasks, and improve project organization? Provide examples of how these tools can enhance collaborative efforts.
 They are crucial for effective project management, allowing teams to organize, prioritize, track, and discuss tasks within a repository, providing a centralized platform for collaboration and ensuring everyone is aware of the project's status and upcoming work, especially when dealing with complex projects with multiple contributors. 
A perfect example is the use of issues and projects board in the design of a Mobile banking application. This helps the developers and project manager track issues that are backlogs, bugs, changes to be made, spaces that require improvement say saving of beenficiary details, transfer limit increase, user experience, etc. It helps the team have a holistic view of the entire process and see what needs to be fixed and how. 

## Reflect on common challenges and best practices associated with using GitHub for version control. What are some common pitfalls new users might encounter, and what strategies can be employed to overcome them and ensure smooth collaboration?
 Common challenges include:
- Loss of history or memory
- Merge conflicts
- Access control issues
- inconsistent documentation

  Strategies to overcome these challenges
  -Use clear branching startegies
  -Regularly update documentation
  -Back up repositories
  -Implement role-based access controls 
  

