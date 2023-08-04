# Polycode MultiChain Token - Powered by ChainLink CCIP

The blockchain technology landscape is moving rapidly to a multi-chain ecosystem, with many networks, rollups L1s/L2s/L3s. The new thesis of blockchain
is the development of App Specific Blockchains or AppChains, which host certain dApps or dApp ecosystems. With this new way of looking at the world, a 
few novel problems arise. 

### 1. Composability / Atomicity
One of the main aspects of smart contract blockchains, which enabled them to grow into a vibrant ecosystem they are today is the composability of smart contracts. The smart contracts which handle assets, exist on the same blockchain & in the same namespace as the smart contracts which provide lending, trading, staking and other services. 

This has an implication of protocols which can seamlessly implement other protocols. One of the prime examples of composability is yEarn Finance, which wraps around large DeFi protocols like Curve, Aave, MakerDAO & others to execute strategies which optimize yield for investors or stakers. Without composability - this would be (essentially) impossible.

### 2. Frontend development / Independent frontends
In a world with one EVM blockchain - building frontends for smart contracts was very simple. You would implement your functionality, get the RPC node from the wallet provider which uses your 
