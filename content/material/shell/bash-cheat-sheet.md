---
title: "Bash Cheat Sheet"
draft: true
tags: ['shell', 'bash']
courses: [ 'info3', 'info2']
languages: ['shell']
---

### Preparations
#### Finding a Shell

On all *nix systems, you will already have a shell - if you run a graphical desktop, look for something called "terminal".

On MacOS, there is the [terminal.app](https://support.apple.com/de-de/guide/terminal/welcome/mac) - I prefer [iTerm](https://iterm2.com/).

On windows, use the [Windows Subsystem for Linux](https://learn.microsoft.com/de-de/windows/wsl/). For quick tryouts you may already have a gitbash installed.

Another quick way to get a shell is using linux image within Docker, e.g.

```bash
docker run -it ubuntu /bin/bash
```

You can also run a virtual machine on [Windows](https://learn.microsoft.com/en-us/linux/install)


#### General Tips & Info

Everything you enter after the prompt is either an internal shell command (e.g. cd, exit, echo - depending on the shell) or the name of an executable found in the path.

If it is neither, you get a "command not found".

### Cheat Sheet

#### Various Things

```bash
date # display or set date and time
df # display free disk space
du # display disk usage statistics

```

#### Things you may encounter

```bash
sudo # execute a command as another user, usually root
```
#### Navigation in the Filesystem