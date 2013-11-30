# git-versioning

This is a git sub-command which provides automatic generation of the new version tag.

See also: [Semantic Versioning](http://semver.org/)

## Installation

1. Download [it](https://raw.github.com/akkunchoi/git-versioning/master/git-versioning)
2. and put on PATH you like  

## Usage

Now, 
    
    $ git tag
    v0.0.1 
    v0.1.2
    v0.1.3

and you run a following command

    git versioning up -p

then the new version tag is created!
    
    $ git tag
    v0.0.1 
    v0.1.2
    v0.1.3
    v0.1.4

## Options

   --pre
   --post
   --major, -m
   --minor, -i
   --patch, -p
   --commit, -c
   --all, -a


