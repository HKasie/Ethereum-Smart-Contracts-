# Ethereum-Smart-Contracts-
### How To Run Smart contracts on Ethereum blockchain.

### Smart Contract Descriptions:

ERC20Token.sol: project to create a smart contract for an ERC20 standard token named DMV.

MultisigWallet.sol: A smart contract to create a multi signature wallet that has satisfies following requirements: 
 * Sets approval for a the transfer request.
 * Update the Transfer object and the mapping to record the approval for the msg.sender.
 * When the amount of approvals for a transfer has reached the limit, the amount should be transfered to the recipient.
 * An owner should not be able to vote twice.
 * An owner should not be able to vote on a tranfer request that has already been sent.

CryptoBank.sol: smart contract to create a cryptobank for depositing, withdrawing and transfering crypto to and from different addresses. Requires the import of two more smart contracts:
  * Ownable - this is a smart contract that ensures the msg.sender is the owner before the withdraw fundtion can execute.
  *  Destroyable - this smart contract is for selfdestruct, the code and storage associated with the contract will be removed from the Ethereum's World State.
  

### How to run Smart Contarcts
1. Compile and deploy the smart contracts on Remix.

2. To compile and deploy the CryptoBank smart contract you will need to the Ownable and destroyable smart contracts as imports into the CryptoBank.
