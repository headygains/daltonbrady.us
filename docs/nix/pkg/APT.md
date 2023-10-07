# apt
- [Wikipedia](https://en.wikipedia.org/wiki/APT_(software))

## manpages
- [ubuntu 20.04 (focal)](https://manpages.ubuntu.com/manpages/focal/man8/apt.8.html)
- [ubuntu 22.04 (jammy)](https://manpages.ubuntu.com/manpages/jammy/man8/apt.8.html)

## Details
In Debian-based Linux distributions like Ubuntu, both `apt` and `apt-get` are available, but they are separate command-line tools. They serve similar purposes, which is to manage packages on your system, but they have some differences in terms of usability and features.

1. `apt-get`: This is the older and more established package management tool. It has been around for a long time and is known for its reliability. You can use it to install, remove, and manage packages on your system. Some common `apt-get` commands include `apt-get install`, `apt-get remove`, and `apt-get update`. It uses a more explicit syntax, and its commands often require the use of `sudo` for administrative privileges.

2. `apt`: `apt` is a newer package management tool that provides a more user-friendly and intuitive interface. It is considered a higher-level wrapper around `apt-get` and other APT (Advanced Package Tool) tools. `apt` simplifies many common package management tasks and often does not require the use of `sudo`. It provides more detailed and informative progress bars and messages compared to `apt-get`, making it easier for users.

Both `apt` and `apt-get` are part of the same `apt` package, so when you install one, you typically get the other as well. You can choose to use either of them based on your preference and familiarity with the command-line interface. `apt` is often recommended for beginners and for its ease of use, while `apt-get` is still widely used and appreciated for its robustness and scripting capabilities.

## Command Overview (2023)
### apt
Provides a set of command-line tools for package management. 
#### samples
`apt install pkg_name`

> Auto accept install reqs

`apt install -y pkg_name`

> List installed packages

`apt list --installed`

> Purge package

`apt purge pkg_name`

> Remove package(s)
`apt remove pkg_name pkg_name_2`

### apt-get 
A command-line tool for handling packages, including installation, removal, and upgrades.

### apt-cache
Used to query and display information about packages in the package cache, such as searching for packages and showing package details.

#### samples
`apt-cache search pkg_name`

### apt-config
Allows you to query or modify APT configuration settings.

### apt-mark
Used for marking packages as manually or automatically installed.

### apt-key
Manages APT keys, which are used to verify the authenticity of packages.

### aptitude
An interactive text-based package manager with a curses-based user interface.

### aptdcon
A D-Bus service for managing packages.

### apt-shell
A command-line shell for interacting with APT repositories.

### apt-listchanges
Displays changes in package release notes during package upgrades.

### apt-ftparchive
Used for creating APT archive index files.

### apt-show-versions
Displays package version information.

### apt-transport-https
A transport method for APT that allows secure communication over HTTPS.