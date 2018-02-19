# testnetfaucet

testnetfaucet is a simple web app that sends a configurable amount of testnet
HX via an rpcclient connection to an instance of hxwallet.

## Installation

## Developing

``` bash
git clone https://github.com/hybridnetwork/testnetfaucet.git
cd testnetfaucet
dep ensure
go install
```

Start hxwallet with the following options.  

```bash
hxwallet --testnet -u USER -P PASSWORD --rpclisten=127.0.0.1:19111 --rpccert=$HOME/.hxwallet/rpc.cert
```

Configure and start testnetfaucet

```bash
mkdir ~/.testnetfaucet
cp sample-testnetfaucet.conf ~/.testnetfaucet/testnetfaucet.conf (and edit appropriately)
testnetfaucet
```

## Contact

If you have any further questions you can find us at:

## Issue Tracker

The
[integrated github issue tracker](https://github.com/hybridnetwork/testnetfaucet/issues)
is used for this project.

## License

testnetfaucet is licensed under the [copyfree](http://copyfree.org) ISC License.

