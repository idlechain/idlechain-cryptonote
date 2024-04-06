# IDLEChain Project

- Copyright (c) 2024 The IDLEChain Project.
- Portions Copyright (c) 2023 The Mangonote Project.
- Portions Copyright (c) 2014-2022 The Monero Project.
- Portions Copyright (c) 2012-2013 The Cryptonote developers.

## How to run
### Linux
```
apt-get install build-essential cmake pkg-config libboost-all-dev libzmq3-dev libssl-dev libpgm-dev libnorm-dev libunbound-dev libsodium-dev libunwind8-dev liblzma-dev libexpat1-dev libgtest-dev ccache doxygen graphviz qttools5-dev-tools libhidapi-dev libusb-1.0-0-dev libprotobuf-dev protobuf-compiler libudev-dev
wget https://idlecalypse.cc/latest.tar.gz
tar xzvf latest.tar.gz
cd idlechain
chmod 755 *
./idlechaind
```
### Windows

Download, unzip and run idlechaind.exe: https://idlecalypse.cc/latest-win64.zip

## How to create a wallet
### Linux
Run and follow the steps:
```
./idlechain-wallet-cli
```
### Windows
Run idlechain-wallet-cli.exe and follow the steps.

## How to mining
Once your idlechaind.exe daemon is synced, run in daemon windows:
```
start_mining YOUR_WALLET NUMBER_THREADS
```
Example (wallet XM33utX...mK8oX5J, 4 threads):
```
start_mining XM33utXBM4tiR6cYxMpASFXNAdzLy2kTbXxBTxsJLwvyMhyuxE6cZeqJ37U5vGYn9cFJDLE75ocYV2mnGehZFSqk1zmK8oX5J 4
```
Stop mining:
```
stop_mining
```
Show more commands:
```
help
```

## How to compile
https://github.com/monero-project/monero?tab=readme-ov-file#compiling-monero-from-source

## Links
Website: https://idlecalypse.cc/
Download: https://github.com/idlechain-project/idlechain/releases
