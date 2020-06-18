# Command Line

---

# Contents

1. Bash
2. Man
3. Git
4. Creating Files And Directories
5. Navigate And Find Files
6. Manipulation Files
7. Vim
8. Connect To A Server

---
 
 # Bash
 
 Bash is a Unix shell and command language.
 
 - Jump to the front of command line.
 ```
 Ctrl+a
 ```
 - Clear the command line.
 ```
 Ctrl+l
 ```
 ```
 clear
 ```
 
 ---
 
 # Man
 
 Man is the system's manual page.
 
 ```
 man bash
 man git
 ```
 
 ---
 
# Git

Git is a free and open source distributed version control system.

```
git init
git clone
git status
git add
git commit -m 'Commit message'
git push
```

---
# Creating Files And Directories

It's easy to create files from the command line.

```
touch file_1.txt
echo "hello textfile" > file_2.txt
nano file_3.txt
echo "more hello" >> file_2.txt
vim file_3.txt
mkdir mydir
```

---
# Navigate And Find Files

With the command line you're never far away from finding your files.

```
ls
ls -lah
cd mydir/hello
cd ..
cd ../..
find / -name catpic
find . -name catpic
ack
```

---

# Manipulating Files

You can easily remove, update timestamp, and change the content of files.

```
touch -d "2 hours ago" file_1.txt
rm file_1.txt
echo "more content" >> file_2.txt
nano file_2.txt
mv file_2.txt file_newname.txt
cp file_2.txt file_3.txt
cp file_2.txt{,.bkp}
```

---

# Vim

```
vim myfile.txt
Insert
ESC
:help vimtutor
:wq!
```

---

# Connect To A Server

```
ssh root@1.2.3.4
ssh root@ip
```

---