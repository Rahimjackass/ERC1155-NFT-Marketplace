Things to think about !!!! 

- Draw a clear roadmap of the platform's Staking capability

- Burning capability ( What Media means by saying burning capability, It needs to be cleared that if they burn they their NFTs where the money should come from to reward them )

- Do we certainly need Dedicated gateways ( Pinata ) for faster data fetching? Or is it unnecessary?

- NFT.Storage: ( https://nft.storage/docs/how-to/mint-erc-1155/ ) ( Decide between infura, alchemy, nft.storage, Pinata, ... )

- **Dynamic NFTs** Tell media about this concept on your next meeting

- **Add type check for inputs**, only integers in number related ones,

- **Put the environment vairbales in the .env file**

- **Add some feature to handle the case when the transaction is rejected or canceled or whatever! Think how you can overcome this concern**

- You have enabled experimental feature (appDir) in next.config.js. **What is this statement?** resolve it

- Put external variables (drop down values) in another file, Implement alphebatic order on drop down

- **Add wallet connect warning to _App.js** to ask users to connect wallets at the start

- You'll need this **https://headlessui.com/react/dialog**, **MaterialUI**

- **While the nft is getting minted, the position of the photo is not proper ( somewhere below the transaction state message )**

- **Decimals cannot be entered within the listing price input**

- **Figure out a solution to force users connect their wallet after opening the website**

- **What is hydrating in Nextjs projects?**

- **Watch some video around "How to develop a ERC1155 marketplace" to fix the bug of marketplace ( second time listing a token ), Take a deep look at their smart contracts **

- Thirdweb3

************************************************
Priorities:
- **(1) Dedicated Gateway**
- **(2) Tether based payments on Polygon**
- **(4) Staking or a similiar solution for reward distribution**

************************************************
Essential needs of the projecet:
- Tokens are burnable, the minter can take them back and burn them
- ROI Smart contract; It should represents ROI and caluclate gains for holders based on the duration, and distribute the rewards later



************************************************
Listing Subphase needs:
- Each token should be listed seperately, giving them different prices to be shown in the gallery
( **index.js** & **my-nfts.js** need to be changed, we can no longer use third partys for retrieving NFTs because we want tokens of a same token id have a different price and this cannot be achieved with the third party approach )
- Each token number of a specific nft will have a unique identifier ( like token Id ), unique ROI, and unique price



************************************************
Buying Supphase needs;
- Each token needs to have a seperate page
- A table of the history of the NFT ownership transfers should be designed at the bottom of the page



************************************************
R&D questions:
- (1) What if we want to provide our own token ( Maleki Token ) for the whole ecosystem, what are the drawbacks and advantages?
- (2) Can we integrate RamzRial into our project? Does RamzRial work with Polygon?
- (3) Can we operate transactions with a stablecoin?



************************************************
Auction phase:
- We are going to add an auction feature for listing



************************************************



