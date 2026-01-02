walletool ~ a tool for reading wallet.dat files
===============================================

A utility for extracting cryptocurrency wallet data from wallet.dat files.


## **To set up the software on Windows or macOS,** 
Follow the manual instructions. macOS offers a more intuitive installer with the [DMG download](../../releases).

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