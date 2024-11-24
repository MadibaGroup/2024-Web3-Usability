# colend
https://app.colend.xyz/

## Core Task 01

*Proceed to connect wallet to website with a practical mental model (G1-G3) of what connecting means, why the process is what it is (different web3 apps might use different processes), understanding and avoiding risks (G4-G5), and confirming connection is successful (G3) (via the website and via MetaMask).*

- Site doesn't confirm connection after approving wallet prompt, and only suggests that the wallet is on the "wrong network".
    - Buggy UI. The wallet address and name tag is displayed after switching to the supported network (next step).

## Core Task 02

*Configure wallet to connect to a desired blockchain network (if it is not already on this network). This network has to be supported by the DApp to perform transactions. The supported networks may be different on each DApp.* 

- Clicking the "wrong network" button triggers wallet to prompt for the supported network.

## Core Task 03

*Conduct an operation of the web3 site that does require wallet approval, configure and sign the transaction, understand and avoid risks. Covers token balances, gas fees, approvals, signature, confirming transaction, etc.*

- Need to buy tokens on `CORE Chain` to transact. Bridged tokens on the linked exchange.

- Asks for unlimited approval.

- No estimated changes for the trx.

- Shows a `Add to wallet` option to track the supplied token balance.


## Core Task 04

*Revert, to the extent possible, any past interactions with the DApp. Disconnect the wallet, unapprove tokens, etc.* 

- Disconnect option doesn't disconnect site from the wallet (i.e., can reopen site and connect wallet without approving in the wallet)

## Screenshots
### connect wallet (no confirmation)
![connected wallet](image-67.png)

### supported network
![add network](image-71.png)

### trx prompts
![trx](image-72.png)
![no estimated changes](image-73.png)

### `add to wallet` option
![site dialog](image-74.png)

### disconnect doesn't remove the site from the wallet
![wallet prompt](image-75.png)