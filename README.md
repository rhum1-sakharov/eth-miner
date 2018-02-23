# ETHEREUM MINER

**Ethereum Claymore Miner on Ubuntu Server**

### Requirement

All commands must be typed in a bash nutshell.

**Works only for AMD cards.**

Disclaimer : use at your own risks. 

## Install Ubuntu Server

Download LTS (Long Term Support) ubuntu server version : https://www.ubuntu.com/download/server

Copy your iso image on a bootable usb key.

Tip, you can use rufus or rawrite32 to make your usb key bootable.

## Install Claymore Ethereum Miner

In your console shell, type commands : 

    cd ~
    sudo apt install wget -y
    wget https://github.com/rhum1-sakharov/eth-miner/releases/download/1.0.1/eth-miner.tar 
    tar xvf eth-miner.tar
    ./install-all.sh

Follow the instructions ...

## Usage

When Ubuntu server is started, your miner is already active :)

### Display Claymore console

If you need to view claymore's log : 

    log 
    
### Claymore config

If you need to setup your claymore config : 

    sudo nano /usr/local/current_miner/config.txt

If you need to set your pools and wallet :

    sudo nano /usr/local/current_miner/epools.txt

If you need to restart your miner :

    sudo systemctl restart miner
    
## Donation

Please make a donation for the developer :

    ETH : D484A9BAD41AA5026D9EB66dE28E257B4dCeFCD2
    
