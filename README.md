
Please follow theses instructions to pull the current repository of our project from Github.

	- git pull git@github.com:mouddene/SelfQuiz.git ( todo once !!! )

If you want to apply your locale change to the remote repository:
	for any new features or modifications, please create a new branch (ex : adding auth system):
		- git checkout -b mouddene/auth

	- git add [file modified]
	- git commit -m 'a breiv message to describe your changes'
	- git push origin
on the server we'll merge each branch on the remote repository:
 	- git merge [branch name] ex: git merge mouddene/auth


if you want reset a previous version :
	- git reset [commit hash] (all you commit are logged on a special file, - git log )

for more details please check git documentation it's quite easy.

Please check NEWS.md file for the new configuration requirements.
