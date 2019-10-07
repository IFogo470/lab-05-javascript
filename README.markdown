Last login: Mon Oct  7 14:01:40 on ttys000
v314-ent-011:~ student$ cd Desktop
v314-ent-011:Desktop student$ mkdir ianfogo
v314-ent-011:Desktop student$ cd ianfogo
v314-ent-011:ianfogo student$ cd i
-bash: cd: i: No such file or directory
v314-ent-011:ianfogo student$ pwd
/Users/student/Desktop/ianfogo
v314-ent-011:ianfogo student$ mkdir lab-05-javascript
v314-ent-011:ianfogo student$ cd lab-05-javascript/
v314-ent-011:lab-05-javascript student$ pwd
/Users/student/Desktop/ianfogo/lab-05-javascript
v314-ent-011:lab-05-javascript student$ git init
Initialized empty Git repository in /Users/student/Desktop/ianfogo/lab-05-javascript/.git/
v314-ent-011:lab-05-javascript student$ ls -al
total 0
drwxr-xr-x  3 student  staff  102 Oct  7 14:31 .
drwxr-xr-x  3 student  staff  102 Oct  7 14:29 ..
drwxr-xr-x  9 student  staff  306 Oct  7 14:31 .git
v314-ent-011:lab-05-javascript student$ git config user.name "IFogo470"
v314-ent-011:lab-05-javascript student$ git config user.email "ian.fogo@mail.citytech.cuny.edu"
v314-ent-011:lab-05-javascript student$ git config -l
filter.lfs.clean=git-lfs clean -- %f
filter.lfs.smudge=git-lfs smudge -- %f
filter.lfs.process=git-lfs filter-process
filter.lfs.required=true
core.repositoryformatversion=0
core.filemode=true
core.bare=false
core.logallrefupdates=true
core.ignorecase=true
core.precomposeunicode=true
user.name=IFogo470
v314-ent-011:lab-05-javascript student$ curl -u 'IFogo740' https://api.github.com/user/repos -d '{"name":"lab-05-javascript"}'
Enter host password for user 'IFogo740':
{
  "message": "Bad credentials",
  "documentation_url": "https://developer.github.com/v3"
}
v314-ent-011:lab-05-javascript student$ curl -u 'IFogo470' https://api.github.com/user/repos -d '{"name":"lab-05-javascript"}'
Enter host password for user 'IFogo470':
{
  "message": "Bad credentials",
  "documentation_url": "https://developer.github.com/v3"
}
v314-ent-011:lab-05-javascript student$ curl -u 'IFogo470' https://api.github.com/user/repos -d '{"name":"lab-05-javascript"}'
Enter host password for user 'IFogo470':
{
  "id": 213461118,
  "node_id": "MDEwOlJlcG9zaXRvcnkyMTM0NjExMTg=",
  "name": "lab-05-javascript",
  "full_name": "IFogo470/lab-05-javascript",
  "private": false,
  "owner": {
    "login": "IFogo470",
    "id": 55106466,
    "node_id": "MDQ6VXNlcjU1MTA2NDY2",
    "avatar_url": "https://avatars1.githubusercontent.com/u/55106466?v=4",
    "gravatar_id": "",
    "url": "https://api.github.com/users/IFogo470",
    "html_url": "https://github.com/IFogo470",
    "followers_url": "https://api.github.com/users/IFogo470/followers",
    "following_url": "https://api.github.com/users/IFogo470/following{/other_user}",
    "gists_url": "https://api.github.com/users/IFogo470/gists{/gist_id}",
    "starred_url": "https://api.github.com/users/IFogo470/starred{/owner}{/repo}",
    "subscriptions_url": "https://api.github.com/users/IFogo470/subscriptions",
    "organizations_url": "https://api.github.com/users/IFogo470/orgs",
    "repos_url": "https://api.github.com/users/IFogo470/repos",
    "events_url": "https://api.github.com/users/IFogo470/events{/privacy}",
    "received_events_url": "https://api.github.com/users/IFogo470/received_events",
    "type": "User",
    "site_admin": false
  },
  "html_url": "https://github.com/IFogo470/lab-05-javascript",
  "description": null,
  "fork": false,
  "url": "https://api.github.com/repos/IFogo470/lab-05-javascript",
  "forks_url": "https://api.github.com/repos/IFogo470/lab-05-javascript/forks",
  "keys_url": "https://api.github.com/repos/IFogo470/lab-05-javascript/keys{/key_id}",
  "collaborators_url": "https://api.github.com/repos/IFogo470/lab-05-javascript/collaborators{/collaborator}",
  "teams_url": "https://api.github.com/repos/IFogo470/lab-05-javascript/teams",
  "hooks_url": "https://api.github.com/repos/IFogo470/lab-05-javascript/hooks",
  "issue_events_url": "https://api.github.com/repos/IFogo470/lab-05-javascript/issues/events{/number}",
  "events_url": "https://api.github.com/repos/IFogo470/lab-05-javascript/events",
  "assignees_url": "https://api.github.com/repos/IFogo470/lab-05-javascript/assignees{/user}",
  "branches_url": "https://api.github.com/repos/IFogo470/lab-05-javascript/branches{/branch}",
  "tags_url": "https://api.github.com/repos/IFogo470/lab-05-javascript/tags",
  "blobs_url": "https://api.github.com/repos/IFogo470/lab-05-javascript/git/blobs{/sha}",
  "git_tags_url": "https://api.github.com/repos/IFogo470/lab-05-javascript/git/tags{/sha}",
  "git_refs_url": "https://api.github.com/repos/IFogo470/lab-05-javascript/git/refs{/sha}",
  "trees_url": "https://api.github.com/repos/IFogo470/lab-05-javascript/git/trees{/sha}",
  "statuses_url": "https://api.github.com/repos/IFogo470/lab-05-javascript/statuses/{sha}",
  "languages_url": "https://api.github.com/repos/IFogo470/lab-05-javascript/languages",
  "stargazers_url": "https://api.github.com/repos/IFogo470/lab-05-javascript/stargazers",
  "contributors_url": "https://api.github.com/repos/IFogo470/lab-05-javascript/contributors",
  "subscribers_url": "https://api.github.com/repos/IFogo470/lab-05-javascript/subscribers",
  "subscription_url": "https://api.github.com/repos/IFogo470/lab-05-javascript/subscription",
  "commits_url": "https://api.github.com/repos/IFogo470/lab-05-javascript/commits{/sha}",
  "git_commits_url": "https://api.github.com/repos/IFogo470/lab-05-javascript/git/commits{/sha}",
  "comments_url": "https://api.github.com/repos/IFogo470/lab-05-javascript/comments{/number}",
  "issue_comment_url": "https://api.github.com/repos/IFogo470/lab-05-javascript/issues/comments{/number}",
  "contents_url": "https://api.github.com/repos/IFogo470/lab-05-javascript/contents/{+path}",
  "compare_url": "https://api.github.com/repos/IFogo470/lab-05-javascript/compare/{base}...{head}",
  "merges_url": "https://api.github.com/repos/IFogo470/lab-05-javascript/merges",
  "archive_url": "https://api.github.com/repos/IFogo470/lab-05-javascript/{archive_format}{/ref}",
  "downloads_url": "https://api.github.com/repos/IFogo470/lab-05-javascript/downloads",
  "issues_url": "https://api.github.com/repos/IFogo470/lab-05-javascript/issues{/number}",
  "pulls_url": "https://api.github.com/repos/IFogo470/lab-05-javascript/pulls{/number}",
  "milestones_url": "https://api.github.com/repos/IFogo470/lab-05-javascript/milestones{/number}",
  "notifications_url": "https://api.github.com/repos/IFogo470/lab-05-javascript/notifications{?since,all,participating}",
  "labels_url": "https://api.github.com/repos/IFogo470/lab-05-javascript/labels{/name}",
  "releases_url": "https://api.github.com/repos/IFogo470/lab-05-javascript/releases{/id}",
  "deployments_url": "https://api.github.com/repos/IFogo470/lab-05-javascript/deployments",
  "created_at": "2019-10-07T18:48:39Z",
  "updated_at": "2019-10-07T18:48:39Z",
  "pushed_at": "2019-10-07T18:48:39Z",
  "git_url": "git://github.com/IFogo470/lab-05-javascript.git",
  "ssh_url": "git@github.com:IFogo470/lab-05-javascript.git",
  "clone_url": "https://github.com/IFogo470/lab-05-javascript.git",
  "svn_url": "https://github.com/IFogo470/lab-05-javascript",
  "homepage": null,
  "size": 0,
  "stargazers_count": 0,
  "watchers_count": 0,
  "language": null,
  "has_issues": true,
  "has_projects": true,
  "has_downloads": true,
  "has_wiki": true,
  "has_pages": false,
  "forks_count": 0,
  "mirror_url": null,
  "archived": false,
  "disabled": false,
  "open_issues_count": 0,
  "license": null,
  "forks": 0,
  "open_issues": 0,
  "watchers": 0,
  "default_branch": "master",
  "permissions": {
    "admin": true,
    "push": true,
    "pull": true
  },
  "allow_squash_merge": true,
  "allow_merge_commit": true,
  "allow_rebase_merge": true,
  "network_count": 0,
  "subscribers_count": 1
}
v314-ent-011:lab-05-javascript student$ git remote -v show
v314-ent-011:lab-05-javascript student$ git remote add origin https://github.com/IFogo470/lab-05-javascript.git 
v314-ent-011:lab-05-javascript student$ git remote -v show
origin	https://github.com/IFogo470/lab-05-javascript.git (fetch)
origin	https://github.com/IFogo470/lab-05-javascript.git (push)
v314-ent-011:lab-05-javascript student$ pwd
/Users/student/Desktop/ianfogo/lab-05-javascript
v314-ent-011:lab-05-javascript student$ git status
On branch master

No commits yet

nothing to commit (create/copy files and use "git add" to track)
v314-ent-011:lab-05-javascript student$ 
