This is the steps of installation as listed by the assignment head with comprehensive steps and here are my problems and resolutions listed below
Part 1: Setting Up Git and GitHub
1. Create a GitHub Account: If you don't already have a GitHub account, sign up at
GitHub.com.
2. Install Git: Install Git on your local machine. Follow the installation guide for your
operating system: Git Installation Guide. https://github.com/git-guides/install-git
2
3. Configure Git: Set up your username and email in Git using the following commands:
git config --global user.name "Your Name"
git config --global user.email "your.email@pvamu.edu"
Part 2: Creating a Repository and Initial Commit
1. Create a New Repository: On GitHub, create a new repository named SE-assignment2.
Initialize it with a README.
2. Clone the Repository: Clone your GitHub repository to your local machine using:
git clone https://github.com/your-username/SE-assignment2.git
3. Make Initial Commit: Change current directory to SE-assignment2 (cd SE-
assignment2). Using any editor, create a simple "Hello, World!" program code in
your preferred programming language. Add, commit, and push your changes to
GitHub:
git add .
git commit -m "Initial commit with Hello, World! program"
git push origin main
Part 3: Working with Branches
1. Create a New Branch: Create a new branch called feature-1 for adding a new feature.
git checkout -b feature-1
2. Implement a Feature: Modify your program to include a new feature (e.g., add
printing out “Hi! Your_name”). Commit your changes to the feature-1 branch.
3. Push the Branch to GitHub: Push your branch to GitHub:
git push origin feature-1
Part 4: Collaborating with Pull Request
1. Create a Pull Request (PR): On GitHub, create a pull request to merge feature-1 into
the main branch. Assign the PR to one of your group members.
2. Review a PR: Review a pull request from a classmate. Provide constructive feedback and
approve or request changes.
3. Merge the PR: After the review, merge the pull request into the main branch.
3
Part 5: Resolving Merge Conflicts
1. Simulate a Conflict: Modify the same line of code in both the main branch and a
new branch (feature-2). Push the feature-2 branch and create a pull request.
2. Resolve Conflict: When attempting to merge the PR, GitHub will highlight the conflict.
Resolve the conflict manually in your local repository and push the resolved changes.
Part 6: Project Documentation and Issues
1. Update README: Enhance your README file to include a project description,
installation instructions, and usage examples.
2. Create Issues: Create at least two issues in your repository. Assign one to yourself and
one to a classmate. Use GitHub Issues to track and manage these tasks.
3. Close Issues: Complete the tasks related to the issues and close them.

PROBLEM & SOLUTIONS

# SE-assignment2
Issues I faced along the way include. 
1. improper spelling for github push request to main
2. pathing to get to certain features
3. fully understanding the process to get people available for my pull request along with its set up (inviting and when to merge)
4. getting to the edditing screen
   
Resolution
1. I checked over spelling and corrected it
2. a google search help point me in the direction while exploring
3. Asking classmates and going on past experiences aided me
4. A little bit of exploration around side menu features
