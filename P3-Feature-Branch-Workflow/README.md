# P3 - Feature branch Git workflow

## Aim
To practise making a separate branch for a change and merging it into the main branch.

## Commands
```bash
git status
git branch
git switch -c add-about-section
# Make the required change in the project files
git status
git add .
git commit -m "Add about section"
git switch main
git merge add-about-section
git branch
```

## What I learned
A branch lets me work on a change separately. After checking the changes, I can merge the branch into main. The branch can be removed after merging using `git branch -d add-about-section`.