# Welcome to NFT Minter 👄

All the code in these repos was created based on explaination by HashLips on the main YouTube channel.
youtube channel link mentioned below. 

[📺 YouTube](https://www.youtube.com/channel/UC1LV4_VQGBJHTJjEWUmy8nA)

first step is to clone the rep by using the rep git clone https://github.com/roadtobitcoin/NFT-Minter-Example.git

Then run the command yarn add all after opening the terminal in the directory to download all dependencies.. ###make sure you have yarn install before you run this command

at this point make sure you have contract deployed to block-chain network in my example i have deployed contract on rinkeby testnet

then go to contract on etherscan and copy the ABI and paste it into SRC:>contracts :><make your own file>  --- in my case it's panda.json
  
  My contract address can be found here. - https://rinkeby.etherscan.io/address/0x85e0eadbc66ea4d8637d82d04e7b61e471533da3#writeContract
  
  Once you complete creation of json file then 
  
  go to example_nft_minter\src\redux\blockchain\blockchainActions.js     and change the name of the file with json file you just created 
  
  like below in my case import SmartContract from "../../contracts/Panda.json";
  
  also in same file blockchainActions.js in line no 51 & 54 change with network ID and contract address. 
  
  now go to app.js and change your contract address and configure your smart-contract function based on your contract. 
  
  once done save all file and run yarn start  to run the script
  
  intereact with your contract and you can stop the terminal script by CNRL+C




# example_nft_minter
Use this repo to see how to create a Dapp that can mint NFTs.
