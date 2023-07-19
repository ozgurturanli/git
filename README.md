# My Personal Notes on Git & Github

## 00. Preparation

```
git config --global user.name "Name Surname"
```

```
git config --global user.email "name.surname@domain.com"
```

to list the configuration:

```
git config --list
```

## 01. Create a Repository

Assume that we have a project folder `MyApp` and we would like to create a repository.

In the folder `MyApp` run the following command:

```
git init
```
## 02. Add the Page to the Repository

```
git add index.html
git commit -m "First Commit"
```
## 03. Checking the Status of the Repository

```
git status
```

`git status` command is used to keep monitoring the states of both the working directory and the repository.

## 04. Making changes

Assume that you made some changes in the `index.html` file and would like to stage them.

## 05. Staging the Changes
```
git add index.html
```
`git add` command is used to add the changes to the staging area.

## 06. Staging & Committing
Suppose that you worked on 2 files `index.html` and `style.css`.

If you would like to commit separately, so that you can have different messages and the traceablity, you may do the following:

```
git add index.html
git commit -m "Changes for index.html"
git add style.css
git commit -m "Changes for style.css"
```

If you don't need separate commits, you could also do it like this:
```
git add index.html
git add style.css
git commit -m "Changes for index.html and style.css"
```
Separating staging and committing, you get the chance to easily customize what goes into a commit.

# Additional Resources
1. [Official Git Documentation](https://git-scm.com/doc)
2. [![Git and GitHub for Beginners - Crash Course](https://img.youtube.com/vi/RGOj5yH7evk/maxresdefault.jpg)](https://youtu.be/RGOj5yH7evk)
