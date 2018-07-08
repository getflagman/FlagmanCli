# Flagman Client

A command line interface for bootstrapping and managing [Flagman](https://github.com/getflagman) blockchain apps.

## Installation

```
npm install -g FlagmanCli
npm install -g n
n stable
```

## Usage

```
./bin/FlagmanCli --help

  Usage: flg-cli [options] [command]


  Commands:

    getheight                              Get block height
    getblockstatus                         Get block status
    openaccount [secret]                   Pen your account and get the infomation by secret
    openaccountbypublickey [publickey]     Open your account and get the infomation by publickey
    getbalance [address]                   Get balance by address
    getaccount [address]                   Get account by address
    getvoteddelegates [options] [address]  Get delegates voted by address
    getdelegatescount                      Get delegates count
    getdelegates [options]                 Get delegates
    getvoters [publicKey]                  Get voters of a delegate by public key
    getdelegatebypublickey [publicKey]     Get delegate by public key
    getdelegatebyusername [username]       Get delegate by username
    getblocks [options]                    Get blocks
    getblockbyid [id]                      Get block by id
    getblockbyheight [height]              Get block by height
    getpeers [options]                     Get peers
    getunconfirmedtransactions [options]   Get unconfirmed transactions
    gettransactions [options]              Get transactions
    gettransaction [id]                    Get transactions
    sendmoney [options]                    Send money to some address
    registerdelegate [options]             Register delegate
    upvote [options]                       Vote for delegates
    downvote [options]                     Cancel vote for delegates
    setsecondsecret [options]              Set second secret
    registerdapp [options]                 Register a dapp
    contract [options]                     Contract operations
    crypto [options]                       Crypto operations
    dapps [options]                        Manage your dapps
    creategenesis [options]                Create genesis block
    peerstat                               Analyze block height of all peers
    delegatestat                           Analyze delegates status
    ipstat                                 Analyze peer ip info

  Options:

    -h, --help         Output usage information
    -V, --version      Output the version number
    -H, --host <host>  Specify the hostname or ip of the node, default: 54.152.219.163
    -P, --port <port>  Specify the port of the node, default: 8196
    -M, --main         Specify the mainnet, default: false
```
