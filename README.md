## Cache Resources

#### Guides
- [Cache Daemon](https://github.com/Cache-core/Guides/blob/master/cache-daemon.md)
  - [Public Node](https://github.com/Cache-core/Guides/blob/master/cache-daemon.md#public-node)
  - [Local Node](https://github.com/Cache-core/Guides/blob/master/cache-daemon.md#local-node)

#### Scripts
- [checkpoints.py](https://github.com/Cache-core/Resources/blob/main/scripts/checkpoints.py) create a backup of all known block hash for faster initial sync on new nodes.
  - Example: `python3 checkpoints.py checkpoints.csv` then load node with `--load-checkpoints=checkpoints.csv`
- [makechange.py](https://github.com/Cache-core/Resources/blob/main/scripts/makechange.py) creates mixin aiding with privacy on the Cache blockchain.
  - Example: *Full example within the raw python file*.
