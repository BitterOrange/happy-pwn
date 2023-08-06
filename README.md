# happy-pwn

## Overview

Let me help you initialize your PWN solution: automatically unstrip glibc and get ready for debugging with glibc's source code. What's more, it is fully offline once you successfully build it.

## Installation

Internet connection is required for installation.

```
cd ~/
git clone --recurse-submodules git@github.com:BitterOrange/happy-pwn.git
cd ./happy-pwn/
./setup
```

**AND THEN, NEVER FORGET** to add the directory `~/happy-pwn/bin/` to your environment variable `PATH`.

## Usage

Change your active directory to your pwn solution, and then use

```
happy-pwn
```

That's all. How simple!
