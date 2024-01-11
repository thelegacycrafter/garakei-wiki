---
weight: 0
title: "Setting locally Hugo"
---
# Setup locally
It's easy to setup a local version of Garakei wiki, and just requires you to install the Hugo framework and pull the repository.

## Install Hugo
### On windows.
First off, you should install [Chocolatey](https://chocolatey.org/install). It's a package manager for windows used my programmers. Make sure you install [git](https://git-scm.com/download/win) too.

Run this command to install Chocolatey in an administrator powershell terminal.
```ps
Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))
```

Next, install hugo-extended from chocolatey. In an administrator powershell terminal, run `choco install hugo-extended` to install.

### On Linux

Follow [Hugo's installation guide](https://gohugo.io/installation/linux/). You can install from your distro's package manager, build from source or install from snap.


## Download repository
Clone the [garakei wiki repository](https://github.com/false-fox/garakei-wiki) using your preferred method.

### Run server
CD into the cloned directory using a terminal and run `hugo server --theme hugo-book` to run a dev environment. The local server will be available on your web broswer with the address localhost:1313. That's it. Any edits you make will make the web page reload and appear automatically.

A small note to make is you need to restart the dev environment every time you do something that affects the sidebar, like creating a new page, or changing a page/category's name.