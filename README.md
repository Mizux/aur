aur
===

My archlinux pkbuild

Naming Convention
-----------------

module : module | module-TYPE | module-METATYPE  
TYPE: docs | theme-NAME | sdk | toolkit | VCS  
VCS : git | svn | hg | svn | darcs | bzr  
METATYPE: themes | themes-all  

Metatype are use to define pkbuild wich agregate several dependencies but don't
produce anything.
e.g. Themes list containing a list of popular themes or all ?

e.g.
gtk-theme-mizux
openscenegraph-docs
cuda-sdk
cuda-toolkit

Compile
-------
```sh
makepkg
```
Verify PKBUILD and src.tar.gz
```sh
namcap name
```
Create tarball
--------------
```sh
makepkg --source
```
Install
-------
```sh
makepkg --install
```
