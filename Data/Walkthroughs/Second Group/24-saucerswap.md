# saucerswap
https://www.saucerswap.finance/

## Core Task 01

*Proceed to connect wallet to website with a practical mental model (G1-G3) of what connecting means, why the process is what it is (different web3 apps might use different processes), understanding and avoiding risks (G4-G5), and confirming connection is successful (G3) (via the website and via MetaMask).*

- Connecting to wallet immediately triggers network switch.

## Core Task 02

*Configure wallet to connect to a desired blockchain network (if it is not already on this network). This network has to be supported by the DApp to perform transactions. The supported networks may be different on each DApp.* 

- (T2 merged with T1) No option to choose another network (expected that user understands the supported network from earlier step)

## Core Task 03

*Conduct an operation of the web3 site that does require wallet approval, configure and sign the transaction, understand and avoid risks. Covers token balances, gas fees, approvals, signature, confirming transaction, etc.*

- Initiating a bridge trx navigates to a new website (`hashport`) which asks the user to install a second wallet (`HBAR`) and connect it with the wallet address in MetaMask. Informing the user about this req in the first site would improve G1.


## Core Task 04

*Revert, to the extent possible, any past interactions with the DApp. Disconnect the wallet, unapprove tokens, etc.* 

- Disconnect option doesn't disconnect site from the wallet (i.e., can reopen site and connect wallet without approving in the wallet)

## Screenshots
### add network (no warnings)
![wallet](image-98.png)

### disconnect doesn't remove site from the wallet
![wallet](image-99.png)