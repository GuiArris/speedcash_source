This is the reference code for [SpeedCash (SCS)](http://getspeedcash.org) cryptocurrency.

## SpeedCash (SCS)

- Name: SpeedCash
- Coin Abbreviation: SCS
- Algorithm: CryptoNight
- Maximum Supply: 587,545 SCS
- PoW Hashing Algo: CryptoNight-Lite V7
- Difficulty algorithm: Zawy V2
- Difficulty Target: 60 Seconds
- Emission speed factor: 25
- Minimun transaction fee: 0.00000100
- Pre-mining: 19%
- P2P Port: 27770
- RPC Port: 27771

## How to compile

### Compile on Linux Ubuntu 16

**1. Install dependencies**

- run an update

``
sudo apt-get update
``

- get all dependencies

``
git clone https://github.com/GuiArris/dependencies.git
``

``
bash install_dependencies.sh
``

**2. Get the coin**

``
git clone https://github.com/GuiArris/speedcash_source.git
``

**3. Build**

 Before:
 
 ``
chmod +x external/rocksdb/build_tools/build_detect_platform
``

``
chmod +x external/rocksdb/build_tools/version.sh
``

 After:

``
Make
``



### Credits
Cryptonote Developers, Bytecoin Developers, Monero Developers, Forknote Project, TurtleCoin Developers, Secure Cash Developers
