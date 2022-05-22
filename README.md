# Git/GitHub Workshop

Workshop taken on 21/05/22 on Git, GitHub and Open Source Contributions at RGIPT.

# Git Cheat Sheet

## SETUP

Configuring user information used across all local repositories

```python
git config --global [user.name](http://user.name/) “[firstname lastname]”
```

set a name that is identifiable for credit when review version history

```python
git config --global user.email “[valid-email]”
```

set an email address that will be associated with each history marker

## SETUP & INITIALIZATION

Configuring user information, initializing and cloning repositories

```python
git init
```

initialize an existing directory as a Git repository

```python
git clone [url]
```

retrieve an entire repository from a hosted location via URL

# STAGE & SNAPSHOT

Working with snapshots and the Git staging area

```python
git status
```

show modified files in working directory, staged for your next commit

```python
git add [file]
```

add a file as it looks now to your next commit (stage)

```python
git reset [file]
```

unstage a file while retaining the changes in working directory

```python
git diff

```

diff of what is changed but not staged

```python
git diff --staged
```

diff of what is staged but not yet commited.

```python
git commit -m “[descriptive message]”
```

commit your staged content as a new commit snapshot

## BRANCH & MERGE

Isolating work in branches, changing context, and integrating changes

```python
git branch
```

list your branches. a * will appear next to the currently active branch

```python
git branch [branch-name]
```

create a new branch at the current commit

```python
git checkout
```

switch to another branch and check it out into your working directory

```python
git merge [branch]
```

merge the specified branch’s history into the current one

```python
git log
```

show all commits in the current branch’s history