# git-hooks
Some Git hooks that can be useful to have.

**Install:**
```
git clone https://github.com/Bricco/git-hooks.git
cp git-hooks/* MY-PROJECT/.git/hooks/
chmod +x MY-PROJECT/.git/hooks/*
```

### 1. pre-commit
Checking for php parse-errors and devel/xdebug debug code before the code is commited.

### 2. prepare-commit-msg
Prepare the commit with some jira smart commit features.

### 3. commit-msg
Creates a jira issue and appends the issue-number to the commit message if the commit message starts with the issue-key (but without any number).
