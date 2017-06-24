
# Git push without authentications

* Commands:

git config --global credential.helper 'cache --timeout 7200'

> Store credentials for two hours (7200 seconds).

git push https://github.com/repo.git master

> It is automatically after first authentication