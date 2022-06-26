# Basic Sample Hardhat Project

This project demonstrates a basic Hardhat use case. It comes with a sample contract, a test for that contract, a sample script that deploys that contract, and an example of a task implementation, which simply lists the available accounts.

Try running some of the following tasks:

```shell
npx hardhat accounts
npx hardhat compile
npx hardhat clean
npx hardhat test
npx hardhat node
node scripts/sample-script.js
npx hardhat help
```

## TODO
- https://buildspace.so/p/mint-nft-collection/lessons/ship-it
- [ ] Try IPFS
- [ ] Sell your NFTs - Right now your users only have to pay gas fees to mint your awesome nfts and you're not getting any of that money! There are several ways to alter your smart contract that make the user pay you to mint your transactions, such as adding payable to your contract and using require to set a minimum amount. Since you're dealing with real money here it's best to do your research carefully and ask the experts that your code is safe. OpenZeppelin has a forum where you can ask questions like this one here!
- [ ] Add Royalties - You can also add royalties to your smart contract that would give you a percentage of every future sale of your NFT! Read more about it here: EIP-2981: NFT Royalty Standard
- [ ] Test your contracts locally - If you want to test your contracts more extensively without deploying to a test net like Rinkeby, Hardhat of course will let you do that! Best way to achieve that is to open up a separate terminal window, navigate to your project directory, then run npx hardhat node and keep that window open! Just like in the beginning of the project you'll see a bunch of accounts with lots of ether. In your other terminal window you can run your test scripts and watch it affect your node window!

## Scratch
### 1st contract
https://jsonkeeper.com/b/30TN
{"name":"Buildspace ftw","description":"Self-explanatory lol","image":"https://i.imgflip.com/6klefx.jpg"}

Contract deployed to: 0x0006d43691E6C06C37AaF9ADE9E71990d75C8f55

### 2nd contract - on-chain NFT

{"name":"Buildspace ftw","description":"Self-explanatory lol","image":"data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHByZXNlcnZlQXNwZWN0UmF0aW89InhNaW5ZTWluIG1lZXQiIHZpZXdCb3g9IjAgMCAzNTAgMzUwIj4KICAgIDxzdHlsZT4uYmFzZSB7IGZpbGw6IHdoaXRlOyBmb250LWZhbWlseTogc2VyaWY7IGZvbnQtc2l6ZTogMTRweDsgfTwvc3R5bGU+CiAgICA8cmVjdCB3aWR0aD0iMTAwJSIgaGVpZ2h0PSIxMDAlIiBmaWxsPSJibGFjayIgLz4KICAgIDx0ZXh0IHg9IjUwJSIgeT0iNTAlIiBjbGFzcz0iYmFzZSIgZG9taW5hbnQtYmFzZWxpbmU9Im1pZGRsZSIgdGV4dC1hbmNob3I9Im1pZGRsZSI+V293QnVpbGRzcGFjZVdvdzwvdGV4dD4KPC9zdmc+"}

Contract deployed to: 0xeC19D8Ab6c9196df1Cbf0478801eb27eeDb5412e
Minted NFT #1

### 3rd contract - onchain NFT, automated random words NFTs

string[] firstWords = [ "Fresh", "Fantastic", "Yeet", "Tasty", "Epic", "Legit", "Pure" ];
string[] secondWords = [ "Shawarma", "Doner", "Pizza", "Burger", "Salad", "Pasta" ];
string[] thirdWords = [ "Luffy", "GonFreecss", "Kilua", "Naruto", "Sasuke", "Itachi", "Kakashi", "Sakura" ];

Contract deployed to: 0xB9CDa8dA044b22F3f5eC546052D05AB0ccA1a36A
Minted NFT #1

### 4th - emits tokenid
Contract deployed to: 0x6EB9bE69B05B46C93c5F8DCCAB4ACCF9250772Df

### 5th - with a hard limit 10 on max NFTs
Contract deployed to: 0x2C84EC7BCfBe89754144F25536cAdf7f407a9dB4

### 6th - limit of 20
Contract deployed to: 0xe7159f94bA143C4AD664c41d05bcaa989936D514