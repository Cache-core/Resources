## Cache Resources

#### Scripts

- [checkpoints.py](https://github.com/Cache-core/Resources/blob/main/scripts/checkpoints.py) create a backup of all known block hash for faster initial sync on new nodes.
  - Example: `python3 checkpoints.py checkpoints.csv` then load node with `--load-checkpoints=checkpoints.csv`
- [makechange.py](https://github.com/Cache-core/Resources/blob/main/scripts/makechange.py) creates mixin aiding with privacy on the Cache blockchain.
  - Example: *Full example within the raw python file*.

#### Developer Tools

- [Node Cryptonight Hashing - MoneroOcean Fork](https://github.com/Cache-core/node-cryptonight-hashing)
