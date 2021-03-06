# BlockMedical
This is a collection of the application that interact with the Ethereum smart contract for BlockMed tokens.
The application here are incentivized to interact with the contract by contributing your code or data to IPFS and
register them on Ethereum smart contract BMD. When you start integrating and interacting with
the contract by uploading and registering your IPFS hash for your wallet, you will be granted `BMD` tokens
from the Smart Contract that can be used ot interact with other applications build out that utilize the
same Smart Contract and BMD ERC20 tokens. In the future, when others access your code or data, you will notice that
you will also obtain BMD tokens as part of the authorization for others to access your code and data. As a result,
you will want to label your code and data as accurate as possible for others.

# How to Upload Code and Data
## Web App for Browser
https://github.com/BlockMedical/bc-ipfs is a web-based app that starts a local IPFS daemon along with
a local `npm` web-server. Behind the scene, it also tap into Ethereum blockchain for you to interact with
the Smart Contract. The wallet requires you to use FireFox browser to interact with Ethereum.

Prerequisite:
1. You will need to have Docker installed first, see: https://docs.docker.com/install/
2. [Firefox](https://www.mozilla.org/) browser needs to be installed along with [MetaMask](https://metamask.io/)

Install and Run (For Mac OSX User):
1. Download the zip file from this Github repository https://github.com/BlockMedical/bc-ipfs/archive/master.zip
2. Unzip it and run the command from a Terminal `run.sh` or double-click it. You should see a console pop up and see the following screen running in the background.
![Docker IPFS NPM](https://github.com/BlockMedical/BlockMedical/blob/master/docker_ipfs_npm_running.png)
3. Open **Firefox** and access http://localhost:3000 and you should see the following screen shows up
![Docker IPFS UI](https://github.com/BlockMedical/BlockMedical/blob/master/firefox_localhost3000.png)
4. Click on `Browse` and start uploading your file
5. Unlock your *MetaMask* Wallet and go to MEW Ethereum wallet https://www.myetherwallet.com/#contracts
6. In MEW, you will need to select the Ropstan **Testnet** network.
7. Enter the contract address `0x0861c0b2C9B7dAc3357598D08285329F0c724D44` (Ropsten) and open a text editor for the following file https://raw.githubusercontent.com/BlockMedical/BlockMedical/master/contract.abi.json, and copy/paste the content into the ABI section of MEW.
8. Select the function `registerIPFS` in the drop down and copy/paste your IPFS hash your would like to register
9. That's it. Your MetaMask wallet will provide you a transaction where you can keep track of your registration along with the token.  

## BMD Wallet - Under Development
https://github.com/BlockMedical/BMDWallet is based on an iOS app from Qtum blockchain.
We welcome the community to help out to build and enhance this to tap into our infrastructure and
Ethereum Smart Contract.
