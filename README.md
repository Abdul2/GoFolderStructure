
## My Go Code Structure  ##

I found GO folder structure sometimes a bit confusing, so i decided to document what i think is working for me (for now). 

all my work is locally stored in one folder (called gocode).  my GOPATH is set to $HOME/gocode. my GOROOT is set to /usr/local/go.

my projects are in both github and bitsbucket.

all projects have src / pkg and bin subfolders. 

my repos include src folders of my projects.( i may change this in the future to include re-usable pkgs and binary ) 


    ├── RemoteSystemsTempFiles
    ├── bin
    │   ├── gocode
    │   ├── main
    │   ├── oracle
    │   └── wiki 
    ├── pkg
    │   └── darwin_amd64
    │       ├── bitbucket
    │       │   └── abdul3
    │       ├── github.com
    │       │   ├── go-sql-driver
    │       │   └── lib
    │       └── golang.org
    │           └── x
    └── src
        ├── bitbucket
        │   └── abdul3 [bitsbucket projects]
        │       ├── godatabase
        │       └── wiki
        ├── github.com
        │   ├── abdul2 [githubprojects]
        │   │   ├── GoFolderStructure
        │   │   ├── database
        │   │   └── phonebook
        │   ├── go-sql-driver
        │   │   └── mysql
        │   ├── lib
        │   │   └── pq
        │   └── nsf
        │       └── gocode
        └── golang.org
            └── x
                └── tools



##to do##

describe folder content 
               
               
