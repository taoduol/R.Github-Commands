# A. Prerequisites
1.  Git is installed on your computer:
  👉 You can check with git --version in Terminal or CMD.
2. GitHub account is created.
3. R and RStudio are installed.

# B. Set up Git in RStudio
1. Open RStudio and run: 
  install.packages("usethis")
  library(usethis)
  usethis::use_git_config(user.name = "Your Name", user.email = "your@email.com")

# C. Create a Local R Project with Git
In RStudio:
1. Go to File > New Project > New Directory > New Project
2. Check "Create a git repository"
3. Name your project and create it.

# D. Create a Repository in Github
In Github:
1. Go to Dashboard / Home and select the green 'New' near your repositories list
2. In RStudio Terminal: enter system("git remote add origin https://github.com/yourusername/your-repo.git")
3. system("git commit -m 'message'")
4. system("git push")

# E. View and Test Configuration
1. Navigate the Environment/History pane in the upper right corner and select the Git tab
2. View and click the checkboxes next to  the .gitignore and .Rproj files and select the Commit button in the box
3. In the upper right box of the pop-up, write a message (e.g. this is my first commit / project setup) and select Commit
4. Click on the green upward facing arrow and 'Push' the update to the online Github repository
5. When you edit any file in your repository locally on your computer, the files will show up in the Environment/History pane and you repeat steps 2-4.
