# Block Chain
![](screenshots/blockchain.jpg)

# ZBank
We will create a genesis block from scratch and construct and connect two nodes using geth so that they can be mined for Ethereum.  We will then use a custom testnet node on the MyCrypto platform to send a transaction (test) between public addresses we created.

## Instructions
Run 'puppeth', name your network and select the option to configure a new genesis block:
![](screenshots/img_001.PNG)

Choose the 'Clique (Proof of Authority)' consensus algorithm. Then paste both account addresses from the first step one at a time into the list of accounts to seal:
![](screenshots/img_002.PNG)

Specify ChainID to complete new genesis block configuration:
![](screenshots/img_003.PNG)

Manage existing genesis and export the configuration to a folder:
![](screenshots/img_004.PNG)

A view of the genesis configuration in folder:
![](screenshots/img_005.PNG)

Unlock accounts to setup the nodes:
![](screenshots/img_006.PNG)

Initialize the nodes:
![](screenshots/img_007.PNG)

Startup the nodes:
![](screenshots/img_008.PNG)

Unlock and start mining in node1:
![](screenshots/img_009a.PNG)
![](screenshots/img_009b.PNG)

Under ideal circumstances we would expect a successful mining operation.  In that scenario, you would see little hammer images indicating the mining process is underway.  Instead, as you can see below, our code only generated "Looking for peers" notices due to errors the Bootcamp staff is aware of and working on:
![](screenshots/img_009c.PNG)

Unlock and start Node 2 in a separate GitBash:
![](screenshots/img_010a.PNG)
![](screenshots/img_010b.PNG)

In the Mycrypto app, generate and copy a Private Key for each address:
![](screenshots/img_011a.PNG)
![](screenshots/img_011b.PNG)

Setup custom node:
![](screenshots/img_012.PNG)

Unlock with the Private Key previously copied:
![](screenshots/img_013a.PNG)

Review account balance (shown on right side of image):
![](screenshots/img_013b.PNG)

A balance was generated but due to the previous errors beyond our control, the coin choice of "ZBankCoin" is not reflect and the transfer is not able to proceed.