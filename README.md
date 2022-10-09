# Cross-compiler toolchain

This repository contains compiled GCC for macOS targeting x86 environment and supporting `C` and `CPP`. I needed this toolchain to build my OS and finally switch to higher-realm.
Although coding in `ASM` was fun, we need `C++` eventually to achieve `nirvana`.

### Installation
Everything is already compiled, since making gcc builds took a lot of time. I don't wanna redo all that, so you can just download and play with the binaries. And during making the build I made a typo i.e. instead of using `i386`, I typed `i686` so all binaries are renamed with a prefix `i686-x` inside `i686-elf` folder. Except that everything works.

```bash
$ git clone https://github.com/rajeshmajumdar/cross-compiler-toolchain.git
$ cd cross-compiler-toolchain/i686-elf/bin
$ ./i686-elf-gcc your_awesome_kernel.cpp
```
