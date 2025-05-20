# project
git basics


Bundle - 4, Exercise 1

In this exercise I have managed to create a new repo on github in relation to making it a secondary remote for the main branch and also made changes to the home page and pushed both remotes as depicted below;
   22  git remote add origin https://github.com/Fuad-Jamal/git-copy.git        
   23  git remote add https://github.com/Fuad-Jamal/git-copy.git
   24  git remote add git-copy https://github.com/Fuad-Jamal/git-copy.git      
   25  git status
   26  git add index.html index.html
   27  git status
   28  git commit -m 'secondary remote created'
   29  git push origin main
   30  git push git-copy main

Bundle 4, Exercise 2

Below we went through some of the instructions and followed the steps for this exercise to meet the directions and the whole process is displayed as;
   38  git checkout -b ft/footer
   39  git add footer.html
   40  git commit -m 'adding file to new branch'
   41  git push
   42  git push --set-upstream origin ft/footer
   43  git add footer.html
   44  git commit -m 'adding changes to footer file'
   45  git push
   46  git checkout main
   47  git checkout -b ft/squashing
   48  git merge --squash ft/footer
   49  git commit -m 'footer changes squashing'
   50  git push --set-upstream origin ft/squashing
   51  history
   52  git checkout main