# Prebuilt Lua Rocks

This repo prebuilds various Lua rocks and serves them through github pages.

Modules are currently built for Lua 5.4

## Packages

- lux-lua - https://github.com/lumen-oss/lux

- minijinja-lua - https://github.com/benniekiss/minijinja-lua

- rsjson-lua - https://github.com/benniekiss/rsjson-lua

- rsre-lua - https://github.com/benniekiss/rsre-lua

## Usage

To use the prebuilt rocks, set the github pages url as the `--extra-servers` arg to `luarocks` or `lux`:

```shell
# lux
lx --extra-servers https://benniekiss.github.io/rocks/ install ...

# luarocks
luarocks --extra-servers https://benniekiss.github.io/rocks/ install ...
```
