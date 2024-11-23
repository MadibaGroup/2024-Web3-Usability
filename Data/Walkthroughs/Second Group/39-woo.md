# woo
# https://fi.woo.org/

T1. Proceed to connect wallet to website with a practical mental model (G1-G3) of what connecting means, why the process is what it is (different web3 apps might use different processes), understanding and avoiding risks (G4-G5), and confirming connection is successful (G3) (via the website and via MetaMask).

- Simple option to connect wallet. Shows the (partial) wallet address and wallet balance.

T2. Configure wallet to connect to a desired blockchain network (start from mainnet Ethereum). This network has to be supported by the DApp to perform transactions. The supported networks may be different on each DApp.

- Switching to `BNB Chain` from the dropdown raises multiple errors in the wallet due to RPC provider.

T3. Conduct an operation of the web3 site that does require wallet approval, configure and sign the transaction, understand and avoid risks. Covers token balances, gas fees, approvals, signature, confirming transaction, etc.

- swap trx triggers spending cap request (trx amount).

- estimated changes in the wallet only shown for send amount.


T4. Revert, to the extent possible, any past interactions with the DApp. Disconnect the wallet, unapprove tokens, etc. 

- Disconnect option doesn't disconnect site from the wallet (i.e., can reopen site and connect wallet without approving in the wallet)

## Screenshots
### add network warnings
![wallet](image-127.png)

### disconnect doesn't remove site from the wallet
![wallet](image-128.png)