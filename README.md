# For Math Wallet DAPP Developer

## Using Math Wallet BinanceChain JS API


```
// config network
var network = {
    blockchain: "binance",
    chainId: "Binance-Chain-Tigris" // testnet: Binance-Chain-Nile
};

// login
mathExtension.getIdentity(network)

// logout
mathExtension.forgetIdentity()

// sign transaction
mathExtension.requestSignature(transaction, network)
```

For details, please find the sample in this repo.

### Download Math Wallet 麦子钱包下载

[http://mathwallet.org](http://mathwallet.org)

If you would like to list your DAPP in Math Wallet, please follow the steps in http://blog.medishares.org/?p=398

如果您希望将您开发的DAPP加入麦子钱包，请查看 http://blog.medishares.org/?p=398


