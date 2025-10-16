# 2400030281-SkillInSemExam1
1 Initialize Git repository
git init

2 Add files to staging
git add .

3 Commit changes with a message
git commit -m "Initial commit - setup student portal project"

4 Create a new branch
git branch feature-login

5 Switch to the new branch
git checkout feature-login

6 Make small change in app.js, then commit
git add app.js
git commit -m "Add login feature in app.js"

7 Switch back to main branch
git checkout main

8 Change style.css, then commit
git add style.css
git commit -m "Update styles in style.css"

9 Merge feature-login into main
git merge feature-login

10 Handle merge conflicts (after resolving manually)
git add .
git commit -m "Resolve merge conflicts"

11 View changes
git diff

12 Undo changes
git reset HEAD fileName
git checkout -- fileName

# Tag the latest commit as v1.0
git tag v1.0
