# ubuntu-22.04-kali-import

This script was only tested on Ubuntu 22.04.  

## What it does
1.  Adds the Kali repository to Ubuntu
2.  Ensures GnuPG is installed
3.  Obtains the Kali repo public key and adds it to apt
4.  Configures Kali repos to not be used during updates to prevent breaking Ubuntu. All desired kali packages must be installed / updated manually
5.  Updates APT
6.  Installs all compatible tools (883 tools in total) as well as VSCode, Filezilla, and git

