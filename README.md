# NANO Light Wallet
![Image of Wallet](https://i.imgur.com/YAt6k45.png)

**Warning this is super beta test, your wallet seed is encoded with a password in seed.txt, it and your private keys are not passed to the server**

### Download Windows Build [Here](https://github.com/BenedictThompson/NANOLightWallet/releases)

## Installation

You will need:
* Python3
* Pip3 (to install the required libraries

To install:
* Go into the python-pure25519-blake directory and install this `python3 setup.py install`
* Using pip3 install
```
urwid
websocket-client
pyblake2 ( Microsoft Visual C++ 14.0 is required on Windows)
bitstring
simple-crypt
configparser
pyqrcode
```
* Run the wallet `python3 gui.py`, if it errors install the necessary missing libs


## Tips
* Currently you only have a single address
* Your setting are in config.ini
* Your wallet seed is kept encoded with a password in the seed.txt file
* The light wallet does all the signing itself so doesnt pass you wallet seed or private keys to the server/network
* You can import another wallet seed using the `import_seed.py` script and decode your current wallet seed with your password using `decode_seed.py`
