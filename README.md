# poa_blockchain_howto

## Environment creation
  - create a new conda environment using conda create -n blockchain python=3.7
  - download [mycrypto](https://download.mycrypto.com/) and [geth](https://geth.ethereum.org/downloads/)
  - navigate into the directory created for geth and activate the conda env

## Create the nodes first
  - Open the terminal and navigate to the directory you created for the geth package
  - For the Proof of Authority blockchain the nodes must be approved prior to creating the genesis block of the blockchain.
  - Utilize these commands to call the geth package and create a new directory for each account, respecitvely named node1 and node2
    - ./geth --datadir node1 account new
    - ./geth --datadir node2 account new

## Create the blockchain
  - Maintain the same directory
  - run the command ./puppeth
    - name your network and copy this into a separate text file
    -

## run the blockchain and send transactions
