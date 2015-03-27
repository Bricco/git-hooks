# git-hooks
Some Git hooks that can be useful to have.

**Install:**
```
git clone https://github.com/Bricco/git-hooks.git
chmod +x git-hooks/*
cp self-post-update .git/hooks/post-update
ln -s $(pwd)/git-hooks/* $(pwd)/MyProject/.git/hooks/

cd MyProject
git config --add jira.project JRE
git config --add jira.user admin.anderssson
git config --add jira.password mysecret
git config --add jira.url https://mycompany.atlassian.net
```



### 1. pre-commit
Checking for php parse-errors and devel/xdebug debug code before the code is commited.

### 2. prepare-commit-msg
Prepare the commit with some jira smart commit features.

### 3. commit-msg
Creates a jira issue and appends the issue-number to the commit message if the commit message starts with the issue-key (but without any number).
