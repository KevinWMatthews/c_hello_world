---
layout: page
title: CMake/gcc
---


Use your system's CMake and gcc to configure, compile, and run.


## Background

If your system already has compatible versions of CMake and gcc installed,
the project can be configured and built easily.


## Prerequisites

  * CMake 3.5+
  * gcc


## Setup

All commands should be run from the out-of-tree build directory:

```
$ cd build_hello_world
```


## Compile and Run

Configure the build system:
```
$ cmake ../hello_world
```
This generates the build system in your build directory
from the `CMakeLists.txt` file in the specified source directory,
`hello_world`.

Compile:
```
$ make
```

Run the resulting executable using:
```
$ ./bin/hello_world
Hello, World!
```
