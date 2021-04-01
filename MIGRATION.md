# Github Migration

  * create empty github repository
  +  git clone --mirror gitlab_repo
  * cd repo
  * git push --mirror github_repo
  * git remote add github git@github.com:__USER__/__REPO__.git
  * git remote set-url origin git@__GITLAB_URL__:__PATH__/__REPO__.git
  * do changes and push them to old gitlab branch
  * when ready push all changes to github
  * git push --all github
