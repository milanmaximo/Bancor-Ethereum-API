# Front-running Bancor


### Usage
Install and run the `geth` Ethereum client first:

```bash
$ sudo apt-get install software-properties-common
$ sudo add-apt-repository -y ppa:ethereum/ethereum
$ sudo apt-get update
$ sudo apt-get install ethereum
$ geth --rpc --unlock 0xYOUR_ACCOUNT_ADDRESS
......wait for the chain to sync........
```

The front-runner code automatically attaches to a running `geth` client:
```bash
$ sudo pip install requests
$ python one_frontrun.py
```
