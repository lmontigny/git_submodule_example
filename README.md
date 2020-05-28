# Git submodule

See doc: https://git.wiki.kernel.org/index.php/GitSubmoduleTutorial

# Intro
2 projects, treated separately  
use a third party lib  
copying the lib = difficult for later use  

keep a Git repository as a subdirectory of another Git repository.

# Usage
```
git submodule add https://github.com/xianyi/OpenBLAS.git
git status
git commit
git push
```
# Cloning a project
```
git clone
git submodule init
git submodule update

OR

git clone --recurse-submodules
```
# change within a submodule
you should first check out a branch, make your changes, publish the change within the submodule, and then update the superproject to reference the new commit.

