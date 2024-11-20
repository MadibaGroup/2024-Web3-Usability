# Methodology for Cognitive Walkthrough 

## Assumptions about the User

- Technical awareness:
  - Comfortable with web 2.0, smartphone apps, browser extensions, browsers
- Blockchain-specific awareness:
  - A wallet contains tokens (or an address that owns tokens)
  - Tokens are digital things of value that can be transacted and wallet tracks the "balance"
  - Transactions are approved by wallet
  - Approval tied to some secret value (key, seed phrases) which is "in" the wallet
  - Where the Bitcoin usability literature leaves off
- Study specific assumptions:
  - Always connect from mainnet Ethereum 



## Tasks

* Installing and configuring MetaMask the software
  * Not part of our study, common to all web3 DApps
* Configuring MetaMask to have an address to receive tokens
  * Not part of our study, common to all web3 DApps
  * Assume user has default settings (address on L1 Ethereum with balance 0)
* Funding the wallet with ETH (for gas costs) and other tokens as necessary
  * Not part of our study, common to all web3 DApps
  * Tricky because of different networks: another user study about Ethereum fragmentation into sidechains and L2s
* Visit a Web3 website and confirm site corresponds to intended website:
  * Not part of our study, common to all web3 DApps
  * Phishing studies have been conducted on web 2.0 that are relevant to this. 
* Proceed to connect wallet to website with a practical mental model (G1-G3) of what connecting means, why the process is what it is (different web3 apps might use different processes), understanding and avoiding risks (G4-G5), and confirming connection is successful (G3) (via the website and via MetaMask).
  * Core task
* Configure wallet to connect to a desired blockchain network (if it is not already on this network). This network has to be supported by the DApp to perform transactions. The supported networks may be different on each DApp. 
  * Core task
  * Might be subsumed by previous core task

* Conduct an operation on the web3 site that does not require wallet approval
  * Not a core task for our study as it does not involve the wallet by definition
* Conduct an operation of the web3 site that does require wallet approval, configure and sign the transaction, understand and avoid risks. Covers token balances, gas fees, approvals, signature, confirming transaction, etc. 
  * Core task

* Revert, to the extent possible, any past interactions with the DApp. Disconnect the wallet, unapprove tokens, etc.
  * Core task 



## Core Tasks

1) Proceed to connect wallet to website with a practical mental model (G1-G3) of what connecting means, why the process is what it is (different web3 apps might use different processes), understanding and avoiding risks (G4-G5), and confirming connection is successful (G3) (via the website and via MetaMask).
2) Configure wallet to connect to a desired blockchain network (if it is not already on this network). This network has to be supported by the DApp to perform transactions. The supported networks may be different on each DApp. 
   * Might be subsumed by previous core task
3) Conduct an operation of the web3 site that does require wallet approval, configure and sign the transaction, understand and avoid risks. Covers token balances, gas fees, approvals, signature, confirming transaction, etc.
4) Revert, to the extent possible, any past interactions with the DApp. Disconnect the wallet, unapprove tokens, etc. 