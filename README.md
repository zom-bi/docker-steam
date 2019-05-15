# Note: this project is deprecated, and should no longer be used as a baseimage for game servers.

## steam
steam installs the steam platform, which is required for most dedicated
source gameserves. This image is useless on its own, but can be used to
spin up gameservers for CS:GO, TF2 or Garys Mod.

### Building steam-base

```
docker build -t zombi/steam .
```
