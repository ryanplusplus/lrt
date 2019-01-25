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

### Install Dependencies
Install dependencies listed in `./deps-dev-0.rockspec`.

```shell
lrt install_deps
```

or

```shell
lrt id
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

### Test
Run Luarocks test command with package paths configured for `./lua_modules`.

```shell
lrt test
```

or

```shell
lrt t
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

### Write Empty Dependencies File
Creates an empty dependency file at `./deps-dev-0.rockspec`.

```shell
lrt write_depfile
```

or

```shell
lrt w
```

or

```shell
lrt init
```
