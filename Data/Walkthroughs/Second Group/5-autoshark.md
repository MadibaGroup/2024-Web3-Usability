# autoshark
https://autoshark.finance/

T1. Proceed to connect wallet to website with a practical mental model (G1-G3) of what connecting means, why the process is what it is (different web3 apps might use different processes), understanding and avoiding risks (G4-G5), and confirming connection is successful (G3) (via the website and via MetaMask).

- Loading the site immediately triggers a wallet prompt to change the network (T2). This assumes the user has decided to use their wallet with the site by just visiting it. It's also not clear if the site can be used without changing to this network. This affects users' understanding about connecting to the site (G1-G3). 

T2. Configure wallet to connect to a desired blockchain network (start from mainnet Ethereum). This network has to be supported by the DApp to perform transactions. The supported networks may be different on each DApp.

- It's not clear if the site only supports BNB chain as there is no option to change network on the site (G1).

T3. Conduct an operation of the web3 site that does require wallet approval, configure and sign the transaction, understand and avoid risks. Covers token balances, gas fees, approvals, signature, confirming transaction, etc.

- Contract name in the transaction prompt is vague and does not explain the action to the user. While this is longer than other DApps, a more clear and simple name can help improve comprehensibility (G6-G8).


T4. Revert, to the extent possible, any past interactions with the DApp. Disconnect the wallet, unapprove tokens, etc. 

- Disconnect option is simple.

## Screenshots
### landing page prompt
![change network prompted after opening site](image-30.png)

### contract name in trx prompt
![trx prompt](image-31.png)

