# repo-lab-1

This is a minimal example to maintain a project that has numerous git repositories through the Google repo tool.

#### 1. Install repo

    Make sure you have a bin/ directory in your home directory and that it is included in your path:

    mkdir ~/bin
    PATH=~/bin:$PATH

    Download the Repo tool and ensure that it is executable:

    curl https://storage.googleapis.com/git-repo-downloads/repo > ~/bin/repo
    chmod a+x ~/bin/repo

#### 2. Download the manifest

    mkdir repo-lab-1
    cd repo-lab-1
    repo init -u https://github.com/passgat/repo-lab-1
    
#### 3. Pull down the repositories as specified in the manifest 

    repo sync 
