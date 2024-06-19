# Task 1: Cloning and Forking

## 1. Cloning a Repository:

  - Choose a public GitHub repository of interest (e.g., a project related to your field of study).

     https://github.com/Wyclifitoh/SbAdminTemplate

  - Clone the repository to your local machine.

    git clone https://github.com/Wyclifitoh/SbAdminTemplate
    cd SbAdminTemplate


  - Explore the repository's structure, files, and history.

    ls -al
    git log --oneline


## 2. Forking a Repository:

  - Fork the same repository you cloned in Task 1 to your GitHub account.

  - Clone the forked repository to your local machine.
        git clone https://github.com/wycliffetyrell/SbAdminTemplate
        cd SbAdminTemplate


# Task 2: Managing Branches

## 3. Creating and Switching Branches:

  - In your local repository, create a new branch (e.g., `feature-update`).

  - Switch to the newly created branch.
    git checkout -b feature-update

## 4. Making Changes and Committing:

  - Make changes to a file or add a new file.
    
    touch demo.txt

  - Commit the changes to the branch
    git commit -m "Added a simple demo txt file "

## 5. Merging Changes:

  - Switch back to the main branch.
    git checkout main


  - Merge the changes from the `feature-update` branch into the main branch.
    git merge feature-update


# Task 3: Handling Conflicts

## 6. Creating Conflicts:

  - In your forked repository, make changes to the same file that you modified in Task 4.
 
    git commit -am "Another change to demo.txt to create conflict"
    

  - Commit the changes.
    git push origin master

# 7. Resolving Conflicts:

  - Create a new branch to resolve the conflict.
    git checkout -b resolve-conflict


  - Resolve the conflict manually in the file.

  - Commit the changes and merge the branch back into `master`.
    git add demo.txt
    git commit -m "Resolved merge conflict in README.md"
    git checkout main
    git merge resolve-conflict

# Task 4: GitHub Pages

## 8. Enabling GitHub Pages:

  - In your forked repository, create a simple HTML file (e.g., `index.html`).
    created a pages.html

  - Enable GitHub Pages for the repository and set the source branch to `master`.
    https://wycliffetyrell.github.io/SbAdminTemplate/pages.html



## 9. Accessing the Published Page:

  - Visit the GitHub Pages URL for your repository and verify that the HTML file is accessible online.
    https://wycliffetyrell.github.io/SbAdminTemplate/pages.html


# Task 5: Open Source Exploration

## 10. Exploring Open Source Projects:

  - Search for an open-source project on GitHub related to your interests.
      https://github.com/flutter/flutter

  - Explore the project's documentation, issues, and contribution guidelines.



## 11. Opening an Issue:

  - Open a new issue in the chosen open-source project, suggesting an improvement, reporting a bug, or asking for clarification.


## Challenges Faced
- Initially faced issues with merge conflicts, but resolved them manually.
- Configuring GitHub Pages took a few attempts to get right.

Submission:

- Push all changes to your forked repository on GitHub.

- Share the link to your forked repository and mention the open-source project you explored with the instructor or submit it as per the class instructions.
# softwaredev
