# Palace🏛️

**A decentralize, permissionless marketplace built^ by Wind core for Wind Metaverse and other Metaverses.**

## Program address
**devnet program address:**<br>`8pbdE2sZbfsYNkifQbPTHcVLNRCLnkNKLMZVHnCkQGMa`

**mainnet-beta program address:**

## Roadmap
|feature|status|description|
|:---|:---|:---|
|Instant buy-sell^|✔️|buy and sell^ instantly.|
|0 transaction fee|✔️|User pays 0 transaction fee to Palace.|
|Permissionless listing|✔️|Anyone with verified Wind NFTs can list their assets.|
|Other listing|⏩|Listing projects outside of Wind protocol.|
|Avatar Rental|⏩|Rent your Avatar to other users without giving up your ownership.|
|Auction|⏩|Auction with conditions: time, price, etc.|
|Marketplace data|✔️|floor price, trade count, marketcap|
|NFTs history data|⏩|historical price, price changes, owner, address|
|User DID data|⏩|public profile, collections, profile pictures, trade data|
|Buyers Offer|⏩|User can offering a negotiated price to a listed NFTs owner.|
|SOL settlement|✔️|Buy and sales settled in Solana.|
|SOC settlement|✔️|Buy and sales settled in Solcrystol.|
|Sell reward|⏩|Get SOC reward by selling^ your NFTs.|
|Buy reward|⏩|Get SOC reward by buying^ others NFTs.|
|Renting reward|⏩|Get SOC reward by renting^ NFTs.|
|Lending reward|⏩|Get SOC reward by lending^ NFTs.|
|Stake reward|⏩|Stake your SOCs and subjected to a locking period.|
|NFTs lending|⏩|Lend^ other assets by collateralizing^ you NFTs|
|Your suggestions?|❓|Reach out!|

## Structure
```
User A
    Palace frontend initialize a transaction by filling the values.

    price 
    item 
    duration 
        
Palace on-chain program 
        
        Receive^ the request and cross-check with its program instruction.
        
        sufficient gas fees? 
        mismatch in value? 
        Correct Ownership?
        ✔️ If yes the NFTs will transfer to the Palace on-chain program. 
Palace Frontend 
        Retrieve^ the data from the on-chain program. 
        ✔️
User B 
        browsing through the listing.. I like it ! initialize a transaction with no negotiation on the said values.
    
     sufficient gas fees? 
       ✔️ If yes the NFTs will transfer from the Palace on-chain program to the User B instantly.
        
Conclusion 
        The process should be instant if successful.         
        The sum will pay directly to the NFTs' previous owner.
        The result is irreversible.
```

### Acknowledgement
The palace marketplace is built^ by Wind core in 02/01/2022. The main contributors^ are^: `Lansane`, `Jacheng`, `Zdream`.
