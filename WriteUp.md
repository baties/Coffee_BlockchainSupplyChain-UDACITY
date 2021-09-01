# Coffee Supply Chain

## Description
Ethereum DApp that demonstrates a Supply Chain flow between a Seller and Buyer. The user story is similar to any commonly used supply chain process. A Seller can add items to the inventory system stored in the blockchain. A Buyer can purchase such items from the inventory system. Additionally a Seller can mark an item as Shipped, and similarly a Buyer can mark an item as Received.

### Actors
* Farmer
* Distributor
* Retailer
* Consumer


### Application WorkFlow Steps 
- There are 4 actors. Farmer, Distributor, Retailer, and Consumer all take part in the creation to consumption of a coffee.
- Farmer initializes the process and transfers its ownership of coffee when the item is packed and ready to be sold
- Distributor buys the packaged coffee from a farmer and sends it to a retailer where the consumer purchases it. Transfering ownership from one to another.

### Actions
* **Farmer** – harvest coffee beans, process coffee beans, pack coffee bags, add coffee palettes, ship coffee palettes.
* **Distributor** – buy coffee palettes.
* **Retailer** – receive coffee palettes.
* **Consumer** – buy coffee items.

### Prerequisites

* *Ganache CLI* v6.12.2 (ganache-core: 2.13.2)
* *Truffle* v4.1.14 (core: 4.1.14)
* *Solidity* v0.4.24 (solc-js)
* *Node* v14.17.5
* *NPM* v6.14.10
* *Web3.js* v1.5.2
* *truffle-hdwallet-provider* 1.0.17

### Additional Libraries Used

-  **Truffle**: To compile, test and migrate contracts.
-  **Solidity**: To compile Solidity codes.  
-  **Web3**: To Connect on BlockChain.
-  **truffle-hdwallet-provider**: Used to Manage connection to Wallet from Truffle.
-  **Infura**: For Deploying Smart Contract.


### Supply Chain Contract Details & Addresses (Rinkeby) :

Test No 1 :
Transaction ID: `0xe71eaa5bdf4ed4440c86496e9d10f4b05578fe9bf274dde1816406c00bb565d0`
Contract Address: [0x36B87Ac265378681aE746aAc823aaBCade831514](https://rinkeby.etherscan.io/address/0x36B87Ac265378681aE746aAc823aaBCade831514)

Test No 2 :
Transaction ID: `0x8413e352aea0f088c3db8c041ceb4edfac739f74adaa67b7c5aa471ec9674d55`
Contract Address: [0x0d0219bAF481BB10cEFF44de7A484860aE4E590e](https://rinkeby.etherscan.io/address/0x0d0219bAF481BB10cEFF44de7A484860aE4E590e)


### Contract Addresses in Rinkeby Network : 

Test No 1 :
- *Farmer Role*      : '0x281147b9bee2677835fb4dc961e62e7ac3865280'
- *Distributor Role* : '0xc64739b0ea996545d87f1ef26a8d9c8ba19d408a'
- *Retailer Role*    : '0x0bd0b8892f03d5878150f94a918d42a51856f026'
- *Consumer Role*    : '0x1f3474fb404741a74f77e5e6a84ae357aebb89dc'

Test No 2 :
- *Farmer Role*      : '0xa4f25324395f20c7c386f865939b6990b4064cd9'
- *Distributor Role* : '0xceddf059f8125d1a023c6dfce1c56c7be4136a22'
- *Retailer Role*    : '0xe241e96cb9f57eaa69b5ced37e7c60f6a2ca930d'
- *Consumer Role*    : '0x0c8a17ff18eb3a807431faaabe0463306d9dfa09'


