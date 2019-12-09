> A open-source graphical desktop wallet client

## What is Samurai

Samurai is PlatON's open-sourced digital wallet desktop client terminal (the client), which can manage basic wallet as well as multi-signature wallet (Joint wallet). It also provides deployment and operational guides of meta-smart contracts for developers, procedures of PlatON private chain building, voting mechanism of block producers according to PlatON economic model, participation rules of PlatON ecosystem governance etc.

In the future, Samurai will provide more rich functions for different users, and we are dedicated to help user to understand and use the PlatON ecosystem better and deeper.

**Core function are listed as below:**

- Building PlatON Private network (a.k. private chain)

- Wallet creation & importation (supports Keystore, Mnemonic phrase, private key)

- Joint wallet(multi-signature) creation and importation 

- Management of wallet balance and transaction details

- Transaction of PlatON Energon

- Contracts debugging and deployment

- Application for block producer with staking

- Participating in block producers voting

Btw, Current Samurai is a beta release. This manual intents to help you solving common issue, please feel free to submit any relevant questions at [issues](https://github.com/PlatONnetwork/Docs/issues),  and welcome to join our technical community!

## How to download and install Samurai

At present，Samurai can run on Windows and Ubuntu, please click [here](https://github.com/PlatONnetwork/Samurai/releases) to download. In the future, Samurai will also support running on MacOS system, Please look forward to it. 

+ **Brief installation instruction on Windows:**

```
1.Download Windows installer samurai.exe.
2.Dual-click the installer and follow the Installation wizard.
3.Shortcut of Samurai will be created on the desktop automatically.
```
**Note**:  

*Just follow the Installation wizard for the first time Samurai being  installed, otherwise,  you need to manually delete the folder (Default path: <u>C:\Users\Username\AppData\Roaming\Samurai</u>，and the Username is the account name of your login to the PC. ) where you saved the Blockchain data and as shown in the following figure, and then follow the installation wizard to install.*

<img src="en-us/user-interfaces/platon-samurai-EN/image/Keystore_address.png" width = "503" height="390"/>  

+ **Brief installation instruction on Ubuntu:**

```
Installation instruction of tar.xz package.
1.Download Linux Samurai package,such as samurai-ubuntu-amd64-xxx.tar.xz(xxx:version number)
2.Right click to extract the installation package.
3.Go to the extracted folder and double-click the executable Samurai to open the client.
```

+ **Brief installation instruction on MacOS:**

MacOS is not supported for the time being

## How to use Samurai

### Network

- [How to join in PlatON TestNet](/en-us/user-interfaces/platon-samurai-EN/_Join-in-a-network.md#how-to-join-in-platon-testnet)
- [How to create a PlatON Private-net](/en-us/user-interfaces/platon-samurai-EN/_Join-in-a-network.md#how-to-create-a-platon-private-net)

### Wallet

- [How to create a wallet](/en-us/user-interfaces/platon-samurai-EN/_Classic-wallet.md#how-to-create-a-wallet)
- [How to import or restore a wallet](/en-us/user-interfaces/platon-samurai-EN/_Classic-wallet.md#how-to-import-or-restore-a-wallet)
- [How to send and receive Energon](/en-us/user-interfaces/platon-samurai-EN/_Classic-wallet.md#how-to-send-and-receive-energon)
- [Why is the test Energon in the wallet cleard](/en-us/user-interfaces/platon-samurai-EN/_Classic-wallet.md#why-is-the-test-energon-in-the-wallet-cleard)

### Joint Wallet

- [What is Joint wallet](/en-us/user-interfaces/platon-samurai-EN/_Joint-wallet.md#what-is-joint-wallet)
- [How to create a Joint wallet](/en-us/user-interfaces/platon-samurai-EN/_Joint-wallet.md#how-to-create-a-joint-wallet)
- [How to add a Joint wallet that has been created](/en-us/user-interfaces/platon-samurai-EN/_Joint-wallet.md#how-to-add-a-joint-wallet-that-has-been-created)
- [How to send and receive Energon with Joint wallet](/en-us/user-interfaces/platon-samurai-EN/_Joint-wallet.md#how-to-send-and-receive-energon-with-joint-wallet)

### Contracts

- [What is wasm contract](/en-us/user-interfaces/platon-samurai-EN/_Contracts.md#what-is-wasm-contract)
- [How to deploy a wasm contract](/en-us/user-interfaces/platon-samurai-EN/_Contracts.md#how-to-deploy-a-wasm-contract)
- [How to add a contract that has been created ](/en-us/user-interfaces/platon-samurai-EN/_Contracts.md#how-to-add-a-contract-that-has-been-created)
- [How to execute a wasm contract ](/en-us/user-interfaces/platon-samurai-EN/_Contracts.md#how-to-execute-a-wasm-contract)
- [What is privacy contract](/en-us/user-interfaces/platon-samurai-EN/_Contracts.md#what-is-privacy-contract)
- [How to deploy a privacy contract](/en-us/user-interfaces/platon-samurai-EN/_Contracts.md#how-to-deploy-a-privacy-contract)
- [How to execute a privacy contract](/en-us/user-interfaces/platon-samurai-EN/_Contracts.md#how-to-execute-a-privacy-contract)

### Blcok Producers

- [How to be a block producer](/en-us/user-interfaces/platon-samurai-EN/_Validator-node.md#how-to-be-a-block-producer)
- [How to improve the probability of becoming a validator](/en-us/user-interfaces/platon-samurai-EN/_Validator-node.md#how-to-improve-the-probability-of-becoming-a-validator)
- [How to vote for a block producer](/en-us/user-interfaces/platon-samurai-EN/_Validator-node.md#how-to-vote-for-a-block-producer)
- [Why are block producers eliminated](/en-us/user-interfaces/platon-samurai-EN/_Validator-node.md#why-are-block-producers-eliminated)
- [How to re-register for block producer if eliminated](/en-us/user-interfaces/platon-samurai-EN/_Validator-node.md#how-to-re-register-for-block-producer-if-eliminated)
- [How to revoke the block producer](/en-us/user-interfaces/platon-samurai-EN/_Validator-node.md#how-to-revoke-the-block-producer)
- [How to redeem the stakes](/en-us/user-interfaces/platon-samurai-EN/_Validator-node.md#how-to-redeem-the-stakes)

