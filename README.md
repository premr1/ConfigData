learning spring cloud by kenny65 udemy course


https://www.udemy.com/microservices-with-spring-cloud

=================== step as of for pushing chnages into git ======================
git init
Initialized empty Git repository in /Users/prem/Downloads/lab-3-server/.git/
MacBook-Pro:lab-3-server prem$ git add README.md
fatal: pathspec 'README.md' did not match any files
MacBook-Pro:lab-3-server prem$ vi README.md
MacBook-Pro:lab-3-server prem$ git add README.md
MacBook-Pro:lab-3-server prem$ vi application.properites
MacBook-Pro:lab-3-server prem$ git add application.properites
MacBook-Pro:lab-3-server prem$ git status
On branch master

Initial commit

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)

        new file:   README.md
        new file:   application.properites

Untracked files:
  (use "git add <file>..." to include in what will be committed)

        .gitignore
        .mvn/
        mvnw
        mvnw.cmd
        pom.xml
        src/

MacBook-Pro:lab-3-server prem$ git commit -m "first commit"
[master (root-commit) 9f16bca] first commit
 2 files changed, 2 insertions(+)
 create mode 100644 README.md
 create mode 100644 application.properites
MacBook-Pro:lab-3-server prem$ git remote add origin https://github.com/premr1/ConfigData.git
MacBook-Pro:lab-3-server prem$ git push -u origin master



===================================================================================
