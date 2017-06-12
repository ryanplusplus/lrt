# lrt
Script for easily working with Luarocks trees. Allows you to configure Lua projects to only reference project-local dependencies in order to isolate them from system-wide dependencies.

## Installation
```shell
luarocks install lrt
```

## Commands
### Install
Install (or reinstall) a rock from Luarocks into `./lua_modules`.

```shell
lrt install <rock name or rockspec> [additional luarocks arguments]
```

or

```shell
lrt i <rock name or rockspec> [additional luarocks arguments]
```

### Run
Run a command with Luarocks binary and package paths configured for `./lua_modules`.

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
