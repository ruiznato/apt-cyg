apt-cyg
=======

apt-cyg is a command-line installer for Cygwin which cooperates with Cygwin Setup and uses the same repository. The sintax is similar to apt-get. Usage examples:

* "apt-cyg install <package names>" to install packages
* "apt-cyg remove <package names>" to remove packages
* "apt-cyg update" to update setup.ini
* "apt-cyg show" to show installed packages
* "apt-cyg find <pattern(s)>" to find packages matching patterns
* "apt-cyg describe <pattern(s)>" to describe packages matching patterns
* "apt-cyg packageof <commands or files>" to locate parent packages 

## Quick Start

First you need to install a few packages with Cygwin setup.exe 
    
```sh
<path_to_download>/setup-x86_64.exe -q -P wget,tar,gawk,xz,bzip2 --no-admin
```

Now you can download and install the script:

```sh
wget https://raw.githubusercontent.com/ruiznato/apt-cyg/master/apt-cyg
install apt-cyg /bin
``` 

Now you can use apt-cyg, for example:

```sh
apt-cyg install vim
```


