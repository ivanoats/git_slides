!SLIDE center
# Just Enough
![git logo](./images/git_logo.png)

!SLIDE center transition=fade
# Inspiration and Icons
## Scott Chacon, Github
[@chacon](http://twitter.com/chacon)

!SLIDE center transition=fade
![camera](images/sony-digital-camera.jpg)
# Git takes Snapshots
## of trees

!SLIDE center transition=fade
# What is a tree?
![working tree](images/tree-workdir.png)

!SLIDE commandline incremental transition=fade

    $ tree things_i_bought
    things_i_bought
    ├── Gemfile
    ├── Gemfile.lock
    ├── README.md
    ├── Rakefile
    ├── app
    │   ├── assets
    │   │   ├── images
    │   │   │   └── rails.png
    │   │   ├── javascripts
    │   │   │   ├── application.js
    │   │   │   └── purchases.js.coffee
    │   │   └── stylesheets
    │   │       ├── application.css
    │   │       ├── purchases.css.scss
    │   │       └── scaffolds.css.scss
    │   ├── controllers
    │   │   ├── application_controller.rb
    │   │   └── purchases_controller.rb
    │   ├── helpers
    │   │   ├── application_helper.rb
    │   │   └── purchases_helper.rb
    │   ├── mailers
    │   ├── models
    │   │   └── purchase.rb

!SLIDE commandline center incremental

## Mac OS X peeps should install tree
### already installed on linux (and even windows!)
 
    $ brew update && brew install tree

!SLIDE center transition=fade
# Three Trees
## HEAD, Index, and Working Directory
![3 trees](./images/trees.png)

!SLIDE center transition=fade
![keepcalm](images/git-reset-head.png)
# What is HEAD?

!SLIDE center transition=fade
# HEAD == the latest commit

!SLIDE center transition=fade
![workflow](images/workflow.png)

!SLIDE center incremental transition=fade
# What is the index? 
* It's also called the staging area
* It's the files you're about to commit
  * but haven't yet
* it's the files you have git added
  * but not committed

!SLIDE incremental transition=fade
# What is 
# the working directory?
* pwd == print working directory
* it's simply the directory for your project
* it can have untracked files

!SLIDE commandline incremental
# What is a remote?

    $ git remote -v
    origin  git@github.com:ivanoats/git_slides.git (fetch)
    origin  git@github.com:ivanoats/git_slides.git (push)

## another git repository

!SLIDE
# What is origin?
* the convention used for the name of the remote git repo on github, bitbucket
* could have called it my_source
* could have called it pancake

!SLIDE
# Branches
## What is master?
* simply a convention for the main branch
* could have called it first
* could have called it cookie_monster

!SLIDE incremental
# Common misconceptions
* don't call a branch "origin"
* don't call a remote "master"
* don't call a branch "index"
* don't call a branch a stick, a chanukah bush, or anything else derogatory


!SLIDE center transition=fade

# Demo

!SLIDE

# Questions?

