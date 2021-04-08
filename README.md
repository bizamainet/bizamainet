
# BIZA - The Most Powerful Infrastructure for Decentralized Applications

Welcome to the BIZA source code repository! This software enables businesses to rapidly build and deploy high-performance and high-security blockchain-based applications.

Some of the groundbreaking features of BIZA include:

1. Free Rate Limited Transactions
1. Low Latency Block confirmation (0.5 seconds)
1. Low-overhead Byzantine Fault Tolerant Finality
1. Designed for optional high-overhead, low-latency BFT finality
1. Smart contract platform powered by WebAssembly
1. Designed for Sparse Header Light Client Validation
1. Scheduled Recurring Transactions
1. Time Delay Security
1. Hierarchical Role Based Permissions
1. Support for Biometric Hardware Secured Keys (e.g. Apple Secure Enclave)
1. Designed for Parallel Execution of Context Free Validation Logic
1. Designed for Inter Blockchain Communication


## Supported Operating Systems

BIZA currently supports the following operating systems:

1. Amazon Linux 2
2. CentOS 7
3. Ubuntu 16.04
4. Ubuntu 18.04
5. MacOS 10.14 (Mojave)

---

**Note: It may be possible to install BIZA on other Unix-based operating systems. This is not officially supported, though.**

---

## Prebuilt Binaries

Prebuilt EOSIO software packages are available for the operating systems below. Find and follow the instructions for your OS:

### Mac OS X:

#### Mac OS X Brew Install
```sh
$ brew tap eosio/eosio
$ brew install eosio
```
#### Mac OS X Brew Uninstall
```sh
$ brew remove eosio
```

### Ubuntu Linux:

#### Ubuntu 18.04 Package Install
```sh
$ wget https://github.com/eosio/eos/releases/download/v2.0.3/eosio_2.0.3-1-ubuntu-18.04_amd64.deb
$ sudo apt install ./eosio_2.0.3-1-ubuntu-18.04_amd64.deb
```
#### Ubuntu 16.04 Package Install
```sh
$ wget https://github.com/eosio/eos/releases/download/v2.0.3/eosio_2.0.3-1-ubuntu-16.04_amd64.deb
$ sudo apt install ./eosio_2.0.3-1-ubuntu-16.04_amd64.deb
```
#### Ubuntu Package Uninstall
```sh
$ sudo apt remove eosio
```

## Uninstall Script
To uninstall the EOSIO built/installed binaries and dependencies, run:
```sh
./scripts/eosio_uninstall.sh
```
