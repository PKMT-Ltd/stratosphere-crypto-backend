# Stratosphere Crypto Backend

Monorepo hosting backend servers which will handle wallet user settings, crypto asset transfer and smart contract interactions. The servers are as follows:
* Wallet Service - handles user settings and wallet interactions
* Crypto Transfer Service - handles requests from Wallet Service for L1 and L2 transfers
* Contracts Service - handles requests from Wallet Service for NFT interactions and, in the future, other contract interactions
* Polling Service - fetches L1 transaction records, L1 auxiliary info e.g. gas price and FX data, mantra chain token data
