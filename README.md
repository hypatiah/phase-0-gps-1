# phase-0-gps-1

386  mkdir gps_one - makes a directory aka workplace in terminal
  387  cd gps_one - change directory - moves the directory
  388  ls -la - ls = list, gives long list of hidden&normal files/folders
  389  git clone https://github.com/hypatiah/phase-0-gps-1.git - copies the clone repo that is on GitHub to your local terminal
  390  cd phase-0-gps-1 - change directory to phase-0-gps-1
  391  touch awesome_page.md - creates a new file 
  392  git status - checks to see if the files are ready to be committed 
  393  git add awesome_page.md - moves from working directory  to staging area where it is ready to be committed as a save point that can be referenced later
  394  git status - see above
  395  git commit -m "Initial commit of awesome_page.md" - makes a save point and the -m means creates a message followed by what is in the quotation marks
  396  git status - see above
  397  git push origin master - sends to GitHub repo to origin from feature branch (in this case also master)
  398  git checkout -b add-command-log - adds a new branch and takes you to it directly
  399  subl README.md - opens file in sublime
  400  history - shows list of command history