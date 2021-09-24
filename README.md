# Demo when creating git from local repo and try to push it to github

1) git init - to initialized empty git repo
2) git status - to check untracked files
3) git add . - to add everything or git add README.md to add a specified 'README.md' file
4) git commit -m "Created Readme.md"
5) Create empty git repo on Github then
git remote add origin +link that copy
6) git push origin master
in the future, to avoid having to push git continuously, use git push -u origin master. -u here stands for upstream