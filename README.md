# Command Line Basics

This repository demonstrates basic Linux command-line operations.

## Commands Used & Their Outputs

### 1. Directory Creation
```bash
mkdir projects
cd projects
mkdir week1 week2
Result:
textprojects/
├── week1/
└── week2/

2. File Creation (in week1/)
cd week1
touch hello.txt
# or: > hello.txt
ls
Output:
texthello.txt

3. Copy & Rename
cp week1/hello.txt week2/hello_copy.txt

4. Delete original
Bashrm week1/hello.txt

5. Create about_me.txt with vim
vim about_me.txt
# Inside vim: press i, type your paragraph, Esc, :wq# command-line-basics
