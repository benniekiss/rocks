# Prebuilt Lua Rocks

This repo prebuilds various luarocks and serves them through github pages.

To use the prebuilt rocks, set the github pages url as the `extra-servers` arg to `luarocks` or `lux`:

```shell
# lux
lx --extra-servers https://benniekiss.github.io/rocks/ install ...

# luarocks
luarocks --extra-servers https://benniekiss.github.io/rocks/ install ...
```
