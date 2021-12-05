# genfstab

This is a standalone version of the `genfstab` tool found in [Arch Linux](https://www.archlinux.org/) 

Some modifications regarding temporary filesystems may be required.

Tested on Fedora 28, Debian 9, CentOS 7

## How to use
Note: switch to root user before running this script.

`sh <(wget -qO- git.io/genfstab) <args>`

or

`sh <(curl -Ls git.io/genfstab) <args>`
  
For example:

`sh <(wget -qO- git.io/genfstab) -U /`

Supply `-h` argument to see usage.

## License

See COPYING for details.
