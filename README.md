# usenet3
A distributed, anti-fragile, Usenet-style system of discussion groups

I've moved this project to <a href='https://gitlab.com/aaron-baugher/usenet3'>GitLab.com</a>, due to GitHub's SJW speech policing.  Migration is very easy:

1. Create an account at GitLab.com.
2. Create a new repository there.
3. It will ask if you want to import the project from GitHub (or a few other places).
4. Select GitHub.
5. It will offer to import all your other projects as well.
6. Say Yes.

7. On your local system:
8.  cd into project directory
9.  `git remote -v` to see current git URL
10. `git remote set-url origin NEWURL` where NEWURL is the GitLab URL (probably the same as before s/github/gitlab/)
11. `git push` will say everything is up-to-date or error if there are differences
