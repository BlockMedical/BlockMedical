# BlockMedical and Privacy
The proposed open protocol will utilize a public Ethereum[7] blockchain for the smart contract execution, while the HIPAA compliant patient identifier data will be stored off-chain such as an AWS encrypted databases as necessary for proper onboarding of medical sensor usage. The private keys of public Ethereum blockchain can be kept on mobile app of patient. In case of loss of mobile app/smart phone, this unique key can have appropriate recovery or replacement mechanisms provided by BlockMed[​ 8]​. Furthermore, the API kit can be extended to support data encryption on top of IPFS as an extra layer of security to keep data encrypted and give users full control of their data. In addition to user data, the open protocol also provides a channel to compute Private Contracts, in other word, confidential code that can be service through off-chain service provider that provides TEE (Intel SGX) backed compute-nodes[9][10]. In Oasis Lab’s Ekiden[11] protocol, clients send inputs to confidentiality-preserving smart contracts, which are executed within a TEE at any compute node. The blockchain stores encrypted contract state.

Read more on our [whitepaper](https://www.slideshare.net/secret/4CGbQSZ5xrHU6w) page 6.

# Smart Contract and Blockchain Privacy
## Ethereum and BMD Utility Smart Contract
We provide the ERC20 on Ethereum for the incentive of sharing data and code ownership within the BlockMed community.
You can review the source code in the [BMD smartcontract](https://github.com/BlockMedical/BMD-smartcontract/tree/encryption-v0.5.3/contracts) repository.
You can review the [BMD-USD Exchange Rate repository here](https://github.com/BlockMedical/BMD-smartcontract/blob/encryption-v0.5.3/contracts/BMDUtilityContract.sol) and the [BMD circulation total supply repository here](https://github.com/BlockMedical/BMD-smartcontract/blob/encryption-v0.5.3/contracts/CustomizedERC20Token.sol#L65). The public chain information displaying the BMD total supply can be found [here](https://etherscan.io/token/0xd9a2dc793e1bbce46e2a7e766d7c76fdaf465e48).

## Ethereum and BMV Investment Contract
We provide the ERC20 on Ethereum for the funding and investment of the BlockMed community.
You can review the source code in the [BMV investment contract](https://github.com/BlockMedical/BMV-ventureasset/tree/v0.3.0/contracts) repository.
You can review the [BMV-USD Exchange Rate repository here](https://github.com/BlockMedical/BMV-ventureasset/blob/v0.3.0/contracts/BMV-USD-ExchangeContract.sol) and the [BMV circulation total supply repository here](https://github.com/BlockMedical/BMV-ventureasset/blob/v0.3.0/contracts/BMVInvestmentContract.sol#L58). The public chain information displaying the BMV total supply can be found [here](https://etherscan.io/token/0x76eec17d8f2a0fad17c9df63524799130834d9d2).

## Blockchain Privacy
We need to maintain privacy on user's data such as health records (HIPAA) or privacy on user inputs for secure computation involving Enigma, Ekiden, and SGX hardware, etc.
