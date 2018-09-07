# BlockMedical
This is a collection of the application that interact with the Ethereum smart contract for BlockMed tokens.
The application here are incentivized to interact with the contract by contributing your data to IPFS and
register them on Ethereum smart contract BMD (TBD-address). When you start integrating and interacting with
the contract by uploading and registering your IPFS hash for your wallet, you will be granted `BMD` tokens
from the Smart Contract that can be used ot interact with other applications build out that utilize the
same Smart Contract and BMD ERC20 tokens.

# Web App for Browser
https://github.com/BlockMedical/bc-ipfs is a web-based app that starts a local IPFS daemon along with
a local `npm` web-server. Behind the scene, it also tap into Ethereum blockchain for you to interact with
the Smart Contract. The wallet requires you to use FireFox browser to interact with Ethereum.

1. Download the zip file from this Github repository https://github.com/BlockMedical/bc-ipfs/archive/master.zip
2. Unzip it and run the command from a Terminal `run-dev.sh`
3. Open Firefox and access http://localhost:3000
4. Click on `choose` and start uploading your file
5. Unlock your MetaMask Wallet and go to https://www.myetherwallet.com/#contracts
6. Enter the contract address 0x59A2b6A0Db84ff5b221b571AB3b7eAaa8F888E85 and copy the ABI as listed below
7. TBD

# BMD Wallet - Under Development
https://github.com/BlockMedical/BMDWallet is based on an iOS app from Qtum blockchain.
We welcome the community to help out to build and enhance this to tap into our infrastructure and
Ethereum Smart Contract.


