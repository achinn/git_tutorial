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
```

---

# Our first change

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

# ... and helps out

```
echo 'hello, world!' > readme.txt
git branch fix_punctuation
git checkout fix_punctuation
git add readme.txt
git commit -m 'fixes readme.txt punctuation'
```
