# Git_summary📝
 
java sukkiri - chapter 13 

## 📎SCM: Software Configuration Management kewords 

**Most common SCM**

- Subversion (SVN)
- Git 

**GIt structures**
- remote repository 
- local repository 
- (stage)
- working tree

**importnat actions** 
- commit 
- push 
- pull 
- clone 
- add 

## 📎.gitignore file 

**example**
```
#開発チーム用 Git登録除外指定
*.class
/class/
dummy
```

## 📎.gitkeep file 

A .gitkeep file is an empty file you add to a folder so that Git will track that folder. Normally, Git only tracks files, not empty folders. So, if you want to keep an empty folder in your repository (maybe because you plan to add files to it later), you can put a .gitkeep file inside. This way, Git knows to keep the folder even though it’s empty.

## 📎branch 
A branch in Git is like a separate line of work. The main branch, often called **master** or **main**, is where the main code lives. When you create a new branch, you're making a copy of this code to work on without changing the main code.

origin/master (or origin/main) is the version of the main branch on the remote (online) repository.
master (or main) is the local version of that main branch on your computer.
You can switch between branches, make changes, and then merge your work back into master (main) when it's ready.

## 📎fork and pull request
A **fork** is like making your own copy of someone else’s project on GitHub. This lets you freely make changes without affecting the original project.

A **pull request** is a way to ask the original project’s owner to look at your changes and, if they like them, add them to the main project. It’s like saying, "Hey, I made some improvements—do you want to include them?"