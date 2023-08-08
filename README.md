# git_assignment_HeroVired

Q1.
  1.1created a repo named as git_assignment_HeroVired
  1.2 create a branch named 'dev'
  1.3 added a given calculatorplus code into dev branch with the file named calculator.py.
  1.4 first pushed this code to dev branch with th following commands
       git add . ,git commit -m "message",git push
       now code got pushed to dev branch
  1.5 next pushed the code to main branch from dev with following command
       git push origin dev:main
  1.6  next made it as release 1 from git console on going to release section right below

  1.7 now created new branch called feature/sqrt and added the sqrt code to it by uncommenting the commented code,next saved this code and pushed to feature/sqrt branch as part of bug fixation code needs to be implemented on divide function in dev branch.
     steps did to push sqrt code to feature/sqrt: git add . ,git commit -m "message",git push
  1.8 switched back to dev branch with command git check out dev and added the bug fixation code for divivde function i.e handling divide by zero.
  1.9 now pushed it to dev branch first to test and check its working fine and then to main,at this stage code had conflict with dev so resolved the conflict on clicking the merge pull request and resolved the errors by removing the >>>>> showcasing the merge issue.
  1.10 next switched back to feature/sqrt and finished its coding and pushed it to feature/sqrt first and then to dev branch to check its working then to main branch and resolved the conflict again by clicking on merge pull request and and resolving >>>>> issue lines.

  1.11 next created version 2 release in git console.

Q2.
   2.1 created a branch named lfs and checked to lfs branch by git checkout lfs
   2.2 run a command on terminal called git lfs install to install git lfs.
   2.3 create a folder called binaryfiless and added 210 mb file to that folder
   2.4 next tracked the bilnary file using git lfs track "binaryfiless/*" it got trackcked by showing tracking and got exited 
   2.5 next tried pushing it with git add .,git commit -m "Added large binary files using Git LFS",git push,at this time it throwed some error regarding lfs on terminal
   2.6 so next followed a steps given on google to make lfs setting change inside repo settings and inside that archives to tick the lfs.
   2.7 next did git push the fikle got pushed to lfs branch.(pushed to lfs branch not to main branch as pushing to main branch was not mentioned.

Q3
  3.1 created a new branch called geometry-calculator: by running git branch geometry-calculator and checking out into it by:git checkout geometry-calculator then  first added area of circle code.
  3.2 uncommented area of circle code and tested and stashed the changes to git stash,after it said changes applied
  3.3 created a new branch called feature/rectangle-area : by running git branch feature/rectangle-area,and checking out into it by:git checkout feature/rectangle-area then added area of rectangle code into it and stashed it by git stash.
  3.4 now switched back to geometry-calculator branch to work on area of circle and push it to dev branch
  3.5 now solved the merge conflict.
  3.6 now switched back to feature/rectangle-area and to work on area of rectangle and push it to dev branch.
  3.7 now finally pushed the code to main branch by solving merge conflicts.
