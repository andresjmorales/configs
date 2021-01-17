# Configuration files

These are some of my bash config files for Ubuntu. I only modified .bashrc but I did create the others.

.bashrc references .bash_aliases and .encryptdir
.bash_aliases references .bash101 whichis basically just a bash -help

encryptdir() is a function to simplify encrypting directories. It still leaves the original folder behind because I need to add additional checking.
Usage: encryptdir [directory]
Output: a file folder_name.tar.gz.gpg
