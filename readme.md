Playing around with SVN.

Similarities with Git
===
Run `svn status` to see what's up.

Run `svn add <filename>` to put files/directories under version control.

Run `svn diff` to see modifications.

Run `svn commit -m "<message>"` to commit the new version of your file to the repository.

Differences with Git
===
Run `svn update` to bring your working copy “up to date” with the repository.

Branching
---
Run `svn copy ^/trunk ^/branches/<branch> -m "<message>"`

References
===
- [SVN Tutorial](http://svnbook.red-bean.com/en/1.6/svn.intro.quickstart.html)
- [Basic merging](http://svnbook.red-bean.com/en/1.6/svn.branchmerge.basicmerging.html)
- Github repo: https://github.com/frnkly/svn/trunk