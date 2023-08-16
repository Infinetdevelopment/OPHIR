# Infinet Contract
## Version for QUOTE

## Things to Note:

### OPHIR.sol
    "intitialTotalSupply" changed to 4 Trillion per client request

### StakableEndowmentContract
    "LAUNCH_TIME" modified to Apr 22, 2023
    "_endowmentSupply" modified to 96 Trillion 
    Total Supply will still be 100 Trillion. (96T + 4T = 100T)


## Contact Info:
    Ray Rastelli, ray@infinet.dev
    Ryan Hungate, ryan@infinet.dev

## Standardized Libaries
    We used openzeppelin for  Context, ERC20, IERC20, IERC20Metadata.

```
These are the main public functions which are documented in the 
StakableEndowmentToken contract.

stakeStart(uint256 stakedPrinciple, uint256 stakedDays)
stakeScrape(address stakerAddr, uint256 stakeIndex, uint40 stakeIdParam)
stakeEnd(uint256 stakeIndex, uint40 stakeIdParam)
allocatedSupply()
currentDay()
reportGlobals()
stakeCount(address stakerAddr)
calculateStakeDays(uint256 tempStartDay, uint256 tempStakedDays, uint256 tempScrapeDay)
calculateInterest(uint256 stakedPrinciple, uint256 stakedDays)

```

## Various other internal function are documented in contract.



