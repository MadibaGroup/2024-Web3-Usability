# ref finance
# https://app.ref.finance/

T1. Proceed to connect wallet to website with a practical mental model (G1-G3) of what connecting means, why the process is what it is (different web3 apps might use different processes), understanding and avoiding risks (G4-G5), and confirming connection is successful (G3) (via the website and via MetaMask).

- Connecting to wallet immediately triggers network switch.

T2. Configure wallet to connect to a desired blockchain network (start from mainnet Ethereum). This network has to be supported by the DApp to perform transactions. The supported networks may be different on each DApp.

- (T2 merged with T1) No option to choose another network (expected that user understands the supported network from earlier step)

T3. Conduct an operation of the web3 site that does require wallet approval, configure and sign the transaction, understand and avoid risks. Covers token balances, gas fees, approvals, signature, confirming transaction, etc.

- To bridge and buy `NEAR` tokens the site directs to `Rainbow` exchange.

- After bridging sufficient tokens in the exchange, the platform initially still suggests the old balance.
    - After several minutes the site updates the balance, allowing the trx.
    - delay possibly due to exchange/NEAR network/dapp site.

T4. Revert, to the extent possible, any past interactions with the DApp. Disconnect the wallet, unapprove tokens, etc. 

- Disconnect is simple and removes site from the wallet.

## Screenshots
### trx on exchange site
![completed trx](image-109.png)

### no predicted changes in wallet
![trx](image-110.png)