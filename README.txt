We were trying out Git. Especially forking, sending pull request and then actually using that very same cloned repositoryto continue working as a collaborator, it goes like this:

do the following steps

1. git remote rm origin

2. git config --global push.default simple

3. git push -u origin master

Tadaa, you can now work with the same local repository but with all permissions. Of course you have to be added as a collaborator by the owner of the repository via Github first.

test
