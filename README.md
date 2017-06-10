# lrt
Script for easily working with Luarocks trees

## Installation
Place [lrt](https://github.com/ryanplusplus/lrt/blob/master/lrt) somewhere on your path.

## Commands
### Install
Install (or reinstall) a rock from Luarocks into `./lua_modules'.

```shell
lrt install <rock name> [additional luarocks arguments]
```

or

```shell
lrt i <rock name> [additional luarocks arguments]
```

### Run
Run a command with Luarocks binary and package paths configured for `./lua_modules'.

```shell
lrt run <command name> [arguments]
```

or

```shell
lrt r <command name> [arguments]
```

### Clean
Remove all rocks install in `./lua_modules`.

```shell
lrt clean
```

or

```shell
lrt c
```
