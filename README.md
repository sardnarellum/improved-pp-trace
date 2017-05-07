# Improved pp-trace

This repo stores SVN patches for Clang, and Clang Tools Extra of pp-trace development as long as they don't get accepted to the main project.

## Getting Started

Download the two patch files and apply them to an existing copy of llvm, clang and clang-extra.

### Prerequisites

0. Get CMake and Python.
1. Check out LLVM:
  - Change directory to where you want the llvm directory placed.
  - `svn co http://llvm.org/svn/llvm-project/llvm/trunk llvm`
2. Check out Clang:
  - `cd llvm/tools`
  - `svn co http://llvm.org/svn/llvm-project/cfe/trunk clang`
3. Check out extra Clang tools:
  - `cd llvm/tools/clang/tools`
  - `svn co http://llvm.org/svn/llvm-project/clang-tools-extra/trunk extra`

### Install patch files

Apply clang.patch on llvm/tools/clang and extra.patch on llvm/tools/clang/tools/extra directories. Further information is available [here](http://clang.llvm.org/get_started.html) about using CMake, make, Visual Studio, etc. If you want to build only pp-trace and its dependencies, run `make pp-trace` target or build pp-trace project in Visual Studio.


