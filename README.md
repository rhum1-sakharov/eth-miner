# eth-miner
Ethereum Claymore Miner on Ubuntu Server

### Requirement

All commands must be typed in a bash nutshell.

## Install Ubuntu Server

Download LTS (Long Term Support) ubuntu server version : https://www.ubuntu.com/download/server

Copy your iso image on a bootable usb key.

Tip, you can use rufus or rawrite32 to make your usb key bootable.

## Install Claymore Ethereum Miner

copy all the repo files in your home directory

In your console shell : 

    cd ~
    ./install-all.sh

Follow the instructions

## Usage

When Ubuntu server is started, your miner is already active :)

### Display Claymore console

If you need to view claymore's log : 

    log 
    
### Claymore config

If you need to setup your claymore config : 

    sudo nano /usr/local/current_miner/config.txt

If you need to restart your miner :

    sudo systemctl restart miner => restart your miner
