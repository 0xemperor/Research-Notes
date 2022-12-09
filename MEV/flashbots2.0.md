# Flash Boys 2.0: Frontrunning, Transaction Reordering, and Consensus Instability in Decentralized Exchanges
- The nature of blockchains should lead to transparent, fair trading and in general a fair defi ecosystem.
    - This paper documents the deployment of "Arbitrage bots" in DEXes which exploit inefficiences and frontrun transactions akin to HFT in traditional finance. 
    - The paper also introduces "Miner extractable value" (MEV) and shows the consensus layer security risks it poses to ethereum 
    - This work largely highlights transaction-ordering dependencies and how traditional forms of financial-market exploitation are being applied to blockchain economies 
- Decentralized exchanges are an alternative to centralized counterparts. 
    - Trades are atomically executed by a smart contract.
    - Funds cannot be stolen by exchange operator because DEXes are non-custodial and even LP(Liquidity Provider) assets are secured by the smart contract. 
    - Exchange logic is also handled by the smart contract.
    - Onchain, smart-contract mediated trades are slow, even cancelled orders appear active. 
        - Adversaries can also frontrun orders by observing them and placing their own order with higher fees (to place their transaction before the DEX order). 
- DEX design flaws can threaten underlying blockchain security.
    - Frontrunning generally exploits information asymmetries, because there are no brokers in decentralized systems, actors engaged in underlying infrastructure have more advantage. 
- NOTE:
    - Something to keep in mind is this paper just considers Etherdelta, Bancor, 0x v1 and v2, Tokenstore and Kyber.
    - This paper was also written even before EIP-1559 went live so there are some differences in how MEV is extracted today, not only that today ETH is a POS network and while they discuss about POS networks in brief it isnt a complete picture of how MEV is extracted today.

[INCOMPLETE...]