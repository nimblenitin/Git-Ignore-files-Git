# Git-Ignore-files-Git

Gitignore tells git which files (or patterns) it should ignore. It's usually used to avoid committing transient files from your working directory that aren't useful to other collaborators, such as compilation products, temporary files IDEs create, etc.

Commands to create a .gitignore file-

```

1. THe following created a .gitignore file which ignores file README.txt and .java.
$ touch .gitignore
$ echo “README.txt”>>.gitignore
$ echo “.java”>>.gitignore

2. Add the files to staging are and check git status it will show file README.txt and .java. has been ignored.
$ git add .
$ git status

```
