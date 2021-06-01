# Elm Kernel Compiler

A fork of [elm/compiler](https://github.com/elm/compiler) allowing the use
of Kernel code.

## Installation

### Linux

```
cd ./installers/linux/
docker build ../../ -f Dockerfile -t elm
docker run -d --name elm elm
docker cp elm:/usr/local/bin/elm ./elm
```

### Other Platforms

Will eventually release for all 3 platforms on npm.
