# Our first repo
```
git init git_tutorial
cd git_tutorial
```

---

# Our first file

```
echo 'hello world' > readme.txt
git status
```

---

# Our first commit

```
git add readme.txt
git status
git commit -m 'adds readme.txt'
git log
```

---

# We make a change

```
echo 'hello world!' > readme.txt
git status
```

---

# Our second commit

```
git add readme.txt
git status
git commit -m 'makes readme.txt louder'
git log
```

---

# Someone else comes along...

```
cd ..
git clone git_tutorial other_git_tutorial
cd other_git_tutorial
git log
git remote -v
```

---

# ... makes a change...

```
echo 'hello, world!' > readme.txt
git branch fix_punctuation
git checkout fix_punctuation
git status
```

---

# ... and commits

```
git add readme.txt
git status
git commit -m 'fixes readme.txt punctuation'
git log
```

---

# They push their branch to us

```
git remote -v
git push origin fix_punctuation
```

---

# We check their changes...

```
cd ../git_tutorial
git branch
git checkout fix_punctuation
git show
```

---

# ... 👍 and merge them into master

```
git checkout master
git merge fix_punctuation
git log
```

---

# Our first repo
```
git init git_tutorial
cd git_tutorial
```

![right, fit](first_repo.png)

---

# Our first file

```
echo 'hello world' > readme.txt
git status
```

![right, fit](first_file.png)

---

# Our first commit

```
git add readme.txt
git status
git commit -m 'adds readme.txt'
git log
```

![right, fit](first_commit.png)

---

# We make a change

```
echo 'hello world!' > readme.txt
git status
```

![right, fit](make_change.png)

---

# Our second commit

```
git add readme.txt
git status
git commit -m 'makes readme.txt louder'
git log
```

![right, fit](second_commit.png)

---

# Someone else comes along...

```
cd ..
git clone git_tutorial other_git_tutorial
cd other_git_tutorial
git log
git remote -v
```

![right, fit](they_clone.png)

---

# ... makes a change...

```
echo 'hello, world!' > readme.txt
git branch fix_punctuation
git checkout fix_punctuation
git status
```

![right, fit](they_make_change.png)

---

# ... and commits

```
git add readme.txt
git status
git commit -m 'fixes readme.txt punctuation'
git log
```

![right, fit](they_commit.png)

---

# They push their branch to us

```
git remote -v
git push origin fix_punctuation
```

![right, fit](push_branch.png)

---

# We check their changes...

```
cd ../git_tutorial
git branch
git checkout fix_punctuation
git show
```

![right, fit](check_changes.png)

---

# ... 👍 and merge them into master

```
git checkout master
git merge fix_punctuation
git log
```

![right, fit](merge_into_master.png)
