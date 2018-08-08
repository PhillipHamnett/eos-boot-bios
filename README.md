# eos-boot-bios
A simple script for booting the bios

It has only been tested on Ubuntu 16.04.
If it doesn't work on your operating system, please open an issue and/or submit a pull request.

This script assumes that you are trying to boot the bios for the first time in a completely fresh run of Nodeos.
To start a fresh run, use the RunNodeosFresh command
To boot the Bios, run the BootBios command

RunNodeosFresh will delete all former blocks in the nodeos system, allowing for a clean start

The BootBios script takes up to 3 arguments:
The first argument is the name of the wallet you want to use, this should not be default or your actual wallet, as this script is intended for testing purposes, and the wallet will be 'purged' before it is used
The second argument is the name of the personal account you want to create
The third argument is the name of the smart contract account you want to create
