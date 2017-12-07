# Class Workflow

## Github setup and general use

- Signup for github account if you don't have one!
- Fork this repo
- Make a folder for our class on your computer
- Clone both the repo and the wiki inside that folder on your computer
- Add a branch for your personal work
  - `git checkout -b` _your_branch_name_ (-b means add a new branch)
- Add the upstream location:
  - `git remote add upstream https://github.com/aaronsherwood/artintel`
- Check remote locations:
  - `git remote -v`
- Merge new examples I might add during the semester to your master branch:
  - `git fetch upstream`
  - `git checkout master`
  - `git merge upstream/master`
- Do all you work on your personal branch, not master:
  - `git checkout yourbranch` 
- Push your work to github:
  - `git add -A`
  - `git commit -m "your commit message"`
  - `git push origin yourbranch`

## Assignment Documentation
All production assignments should be documented. This 
