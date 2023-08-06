# happy-pwn

## Overview

Let me help you initialize your PWN solution: automatically unstrip glibc and get ready for debugging with glibc's source code. What's more, it is fully offline once you successfully build it.

This repository is based on two GitHub repositories:

- [matrix1001/glibc-all-in-one: 🎁A convenient glibc binary and debug file downloader and source code auto builder](https://github.com/matrix1001/glibc-all-in-one)
- [BitterOrange/glibc-source-all: Automatically fetch ALL version of glibc, getting ready for debugging and local build.](https://github.com/BitterOrange/glibc-source-all)

## Installation

Internet connection is required for installation.

Before installation, it is necessary to prepare dependency packages with apt:

```shell
sudo apt install wget patchelf binutils elfutils python3 tar
```

And then begin installation:

```shell
cd ~/
git clone --recurse-submodules git@github.com:BitterOrange/happy-pwn.git
cd ./happy-pwn/
./setup
```

**FINALLY, NEVER FORGET** to add the directory `~/happy-pwn/bin/` to your environment variable `PATH`.

## Usage

Change your active directory to your pwn solution, and then use

```shell
happy-pwn
```

That's all. How simple!
