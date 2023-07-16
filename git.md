# Getting Started With Git

**Source Control**

Source control, or version control, is a way of tracking your files progress over time.

It is usually saved in a series of snapshots and branches, which you can move back and forth between.

**What you can do**

- Distribute your file changes
- over time
- Prevent against data
- loss/damage by creating
- backup snapshots
- Manage complex project
- structures

**Creating GitHub Account**

If you are reading this on the browser, you are likely reading from GitHub. To create a GitHub account, go to [https://github.com/login](https://github.com/login) and sign up. After following the procedure, you need to log in into GitHub. Then we set GitHub Desktop Application.

> While reading through the file below, when you encounter line(s) such as a line written below,
```
$ git status
```
> you will see $ symbol. In README.md file, whenever you see a $ sign, understand that this lines indicates code to be entered in the terminal in particular. In some cases, some authors use $ symbol for language specific commands in the README file.

<br>

### First Time Git Setup

Now that you have Git on your system, you’ll want to do a few things to customize your Git environment.

The first thing you should do when you install Git is to set your user name and email address. This is important because every Git commit uses this information, and it’s immutably baked into the commits you start creating:

```
$ git config --global user.name "John Doe"
$ git config --global user.email johndoe@example.com
```

"John Doe" is a username passed into git and "<johndoe@example.com>" is the mailing address passed into git so as to setup your identity. Please be cautious that the `user.email` should have the same email address as the one used to sign in into GitHub.

**Your default branch name**

By default Git will create a branch called master when you create a new repository with git init. From Git version 2.28 onwards, you can set a different name for the initial branch.

To set main as the default branch name do:

```
$ git config --global init.defaultBranch main
```

**Checking Your Settings**

If you want to check your configuration settings, you can use the command to list all the settings Git can find at that point:

```
$ git config --list
```

**Getting Help**

If you ever need help while using Git, there are three equivalent ways to get the comprehensive manual page (manpage) help for any of the Git commands:

```
$ git help <verb>
$ git <verb> --help
$ man git-<verb>
```

For example, you can get the manpage help for the git config command by running this:

```
$ git help config
```


To use the latest version of Git, you need to update the Git. But be careful with the latest versions and look out for the words such as "recent maintained build" or "maintained build" which means it is Long Term Support (LTS) version and will not crash when working with it. If you install under maintenence build version, you will experience a lot of commands or builds crashing. So, it is advised to look out for such information, not only for Git but for many Open Source applications because commercial applications are packaged and are fully tested before they are sold out in the marketplace.

To update the Git to latest version in Windows, type the following command in the new terminal or powershell window:

    $ git update-git-for-windows


---

### Git Commands We Will Use In This Session

```
$ git clone https://github.com/dhakalnirajan/Python-Workshop.git          //Making a copy of the repo in local device(PC)
$ git init                                                                          //Initialize git in the git folder at local device
$ git status                                                                        //Show file status
$ git add .                                                                         //Add all the file 
$ git commit -m "Commit Message"                                                    //Commit the files
$ git remote add origin https://github.com/dhakalnirajan/Python-Workshop.git  //Connect your local git repo with a remote/online git repo.
$ git push -u origin                                                                //Push(Send) it to the repo
$ git pull                                                                          //Extract the contents from the repo to local device
```

These commands are nice because you can access them anywhere, even offline.

If you don’t need the full-blown manpage help, but just need a quick refresher on the available options for a Git command, you can ask for the more concise “help” output with the `-h` option, as in:

```
$ git add -h
```

**Getting a Git Repository**

You typically obtain a Git repository in one of two ways:

1. You can take a local directory that is currently not under version control, and turn it into a Git
repository, or
2. You can clone an existing Git repository from elsewhere.

In either case, you end up with a Git repository on your local machine, ready for work.

<br>

For more on Git commands, go to:

[https://github.com/nirajand/git-workshop/blob/main/Git.md](https://github.com/nirajand/git-workshop/blob/main/Git.md)

