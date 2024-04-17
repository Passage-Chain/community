# Passage - NFT Staking Requirements
The Steering Committee has identified the following requirements for NFT staking.

## Existing Vault
- Minimum staking period
- Unstaking duration
- Stake NFT
  - Moves NFT to vault contract
  - Can’t transfer or list to sell
- Unstake NFT
- Restake NFT during unstaking phase
- Hooks for calling other contracts upon completion of staking

## New Vault?
- Vault for multiple NFTs staked together from different contracts
  - Users cannot unstake NFTs separately

## New Staking Contract
- Instantiate vaults based on requirements of creator - multiple NFTs or single NFT
- Emit IBC tokens (CW-20 & Native) at specified rates during staking period
  - Tokens deposited into contract by creator
  - Creator can deposit more tokens to contract
