# instadapp
# https://fluid.instadapp.io/

T1. Proceed to connect wallet to website with a practical mental model (G1-G3) of what connecting means, why the process is what it is (different web3 apps might use different processes), understanding and avoiding risks (G4-G5), and confirming connection is successful (G3) (via the website and via MetaMask).

- Simple option to connect wallet. Shows (partial) wallet address after connecting.

T2. Configure wallet to connect to a desired blockchain network (start from mainnet Ethereum). This network has to be supported by the DApp to perform transactions. The supported networks may be different on each DApp.

- Simple dropdown with list of supported networks. Switched to `Base` without any issues/warnings.

T3. Conduct an operation of the web3 site that does require wallet approval, configure and sign the transaction, understand and avoid risks. Covers token balances, gas fees, approvals, signature, confirming transaction, etc.

- Depositing USDC on Base opens spending cap request for the trx amount. Shows confirmation after trx completes.


T4. Revert, to the extent possible, any past interactions with the DApp. Disconnect the wallet, unapprove tokens, etc. 

- Disconnect is simple and removes site from the wallet.

## Screenshots
### spending cap
![wallet](image-123.png)

### trx request
![trx request](image-124.png)