# Palaceðï¸

**A decentralize, permissionless marketplace built^ by Wind core for Wind Metaverse and other Metaverses.**

## Program address
**devnet program address:**<br>`8pbdE2sZbfsYNkifQbPTHcVLNRCLnkNKLMZVHnCkQGMa`

**mainnet-beta program address:**

## Roadmap
|feature|status|description|
|:---|:---|:---|
|Instant buy-sell^|âï¸|buy and sell^ instantly.|
|0 transaction fee|âï¸|User pays 0 transaction fee to Palace.|
|Permissionless listing|âï¸|Anyone with verified Wind NFTs can list their assets.|
|Other listing|â©|Listing projects outside of Wind protocol.|
|Avatar Rental|â©|Rent your Avatar to other users without giving up your ownership.|
|Auction|â©|Auction with conditions: time, price, etc.|
|Marketplace data|âï¸|floor price, trade count, marketcap|
|NFTs history data|â©|historical price, price changes, owner, address|
|User DID data|â©|public profile, collections, profile pictures, trade data|
|Buyers Offer|â©|User can offering a negotiated price to a listed NFTs owner.|
|SOL settlement|âï¸|Buy and sales settled in Solana.|
|SOC settlement|âï¸|Buy and sales settled in Solcrystol.|
|Sell reward|â©|Get SOC reward by selling^ your NFTs.|
|Buy reward|â©|Get SOC reward by buying^ others NFTs.|
|Renting reward|â©|Get SOC reward by renting^ NFTs.|
|Lending reward|â©|Get SOC reward by lending^ NFTs.|
|Stake reward|â©|Stake your SOCs and subjected to a locking period.|
|NFTs lending|â©|Lend^ other assets by collateralizing^ you NFTs|
|Your suggestions?|â|Reach out!|

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
        âï¸ If yes the NFTs will transfer to the Palace on-chain program. 
Palace Frontend 
        Retrieve^ the data from the on-chain program. 
        âï¸
User B 
        browsing through the listing.. I like it ! initialize a transaction with no negotiation on the said values.
    
     sufficient gas fees? 
       âï¸ If yes the NFTs will transfer from the Palace on-chain program to the User B instantly.
        
Conclusion 
        The process should be instant if successful.         
        The sum will pay directly to the NFTs' previous owner.
        The result is irreversible.
```

### Acknowledgement
The palace marketplace is built^ by Wind core in 02/01/2022. The main contributors^ are^: `Lansane`, `Jacheng`, `Zdream`.
