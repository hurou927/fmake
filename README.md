
# fmake

fmake is a simple tool for building c/c++/cu files.

# usage

```fmake [--all|-a] [--clean|-c]```
* all :  build all source files
* clean : remove depfiles and execution files

## Build
```
fmake
fmake --all
fmake -a
```

## Remove
depfiles and execution files.
```
fmake --clean
fmake -c
```

## Remove and Build
remove->build
```
fmake --all --clean
fmake -ac
```


This software is released under the MIT License, see LICENSE.txt.
