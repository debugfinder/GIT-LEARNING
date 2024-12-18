**Beginner-Friendly Notes on Git and GitHub**

## Chapter 1: What is Git?

Git is a tool that helps you track changes in your code or files. It’s like a super-smart diary for your projects, where every change is saved and you can look back at any point in time.

### Key Features of Git:

1. **Version Control:** It keeps track of every change you make in your files.
2. **Branches**: You can create separate lines of work to try out new ideas without affecting the main project.
3. **Backup**: If you mess up, you can go back to a previous version easily.
4. **Collaboration**: Multiple people can work on the same project without conflicts.

### Quiz 1: Understanding Git

1. What is Git primarily used for?
2. Name two features of Git.
3. What does "branch" mean in Git?

---

## Chapter 2: Basic Git Terms

### Terms to Know:

- **Repository (Repo)**: A folder where Git keeps track of your project’s changes.
- **Commit**: A saved version of your project with a message describing what you changed.
- **Branch**: A separate path to work on changes without affecting the main version.
- **Merge**: Combining changes from one branch into another.
- **Pull**: Getting the latest changes from an online repository.
- **Push**: Sending your changes to an online repository.

### Quiz 2: Git Terminology

1. What is a "repository" in Git?
2. Define the term "commit".
3. What is the difference between "pull" and "push"?

---

## Chapter 3: What is GitHub?

GitHub is like a social media platform for your Git repositories. It’s a website where you can store your Git projects online, share them with others, and work together on code.

### Key Features of GitHub:

1. **Online Backup**: Keep your projects safe by storing them in the cloud.
2. **Collaboration**: Work with teammates from anywhere.
3. **Open Source**: Share your projects with the world, or learn from others.
4. **Issue Tracking**: Keep track of bugs or features to add.
5. **Pull Requests**: Suggest changes to a project and discuss them before adding.

### Quiz 3: Exploring GitHub

1. What is GitHub?
2. List three features of GitHub.
3. How does GitHub help with collaboration?

---

## Chapter 4: How Git and GitHub Work Together

1. You create a project on your computer and turn it into a Git repository.
2. You make changes, save them (commit), and push them to GitHub.
3. On GitHub, others can see your project, suggest changes, or contribute new features.
4. You can pull their updates or merge their suggestions into your project.

### Quiz 4: Git and GitHub Workflow

1. How do Git and GitHub complement each other?
2. Explain the basic workflow when using Git and GitHub together.
3. What is the purpose of a "commit" in this workflow?

---

## Chapter 5: Basic Git Commands

### Commands Overview:

1. **Initialize a Git Repository**:

   
bash
   git init


   This starts tracking changes in your project folder.

2. **Check the Status**:

   
bash
   git status


   Shows which files are changed and ready to be saved.

3. **Add Files to be Committed**:

   
bash
   git add filename


   Adds specific files. Use git add . to add all files.

4. **Save Changes (Commit)**:

   
bash
   git commit -m "Your message here"


   Saves your changes with a description.

5. **Push Changes to GitHub**:

   
bash
   git push origin branch-name


   Sends your changes to GitHub.

6. **Pull Updates from GitHub**:

   
bash
   git pull origin branch-name


   Gets the latest changes from GitHub.

7. **Create a New Branch**:

   
bash
   git branch branch-name


   Makes a new branch to work on.

8. **Switch to a Branch**:

   
bash
   git checkout branch-name


   Moves you to the branch you want to work on.

9. **Merge Branches**:

   
bash
   git merge branch-name


   Combines the changes from one branch into another.

### Quiz 5: Command Knowledge

1. What does the git init command do?
2. How do you save changes with a description in Git?
3. Write the command to pull updates from GitHub.

---

## Chapter 6: Steps to Use Git and GitHub

1. **Set Up Git**: Install Git on your computer and configure it.

   
bash
   git config --global user.name "Your Name"
   git config --global user.email "your.email@example.com"


2. **Create a Repository on GitHub**:

   - Go to GitHub, click “New Repository,” and follow the steps.

3. **Link Your Local Project to GitHub**:

   
bash
   git remote add origin https://github.com/username/repo-name.git


4. **Push Your Code**:

   
bash
   git push -u origin main


   Sends your local code to GitHub.

### Quiz 6: Setting Up Git and GitHub

1. How do you configure Git for the first time?
2. What is the purpose of the git remote add command?
3. Explain how to push local code to GitHub.

---

## Chapter 7: Practice Tasks

### Task 1: Setting Up Git

1. Install Git on your computer (if not already installed).
2. Configure Git with your name and email using:
   
bash
   git config --global user.name "Your Name"
   git config --global user.email "your.email@example.com"


### Task 2: Creating a Local Repository

1. Create a new folder on your computer for a sample project.

2. Open the folder in a terminal and run:

   
bash
   git init


   This will create a local Git repository.

3. Create a text file (e.g., example.txt) and add some content.

4. Track the file with Git:

   
bash
   git add example.txt


5. Save your changes:

   
bash
   git commit -m "Added example.txt"


### Task 3: Working with GitHub

1. Create a new repository on GitHub.
2. Link your local repository to the GitHub repository using:
   
bash
   git remote add origin https://github.com/your-username/your-repo-name.git

3. Push your code to GitHub:
   
bash
   git push -u origin main


### Task 4: Collaborating

1. Create a new branch in your local repository:
   
bash
   git branch new-feature

2. Switch to the new branch:
   
bash
   git checkout new-feature

3. Make some changes to the example.txt file and save them.
4. Commit the changes:
   
bash
   git commit -m "Updated example.txt in new-feature branch"

5. Push the new branch to GitHub:
   
bash
   git push origin new-feature

6. On GitHub, create a pull request to merge the new-feature branch into the main branch.

### Quiz 7: Practice Tasks Review

1. Describe the steps to initialize a Git repository.
2. How do you push changes to a new branch on GitHub?
3. Explain the purpose of a pull request in GitHub.
