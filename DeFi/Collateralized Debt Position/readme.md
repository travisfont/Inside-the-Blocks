# Collateralized Debt Positions (CDP)

> **A Collateralized Debt Position is a smart contract where users lock digital collateral to borrow stablecoins or other assets.**
>
> These mechanisms rely on contract-governed liquidation and oracle pricing.
> CDPs ensure solvency through collateral ratios, automatic liquidation triggers, and decentralized risk governance systems — crucial to DeFi’s stability layer.

- https://blog.synthetix.io/synthetix-v3-collateralized-debt-positions-cdp/
- https://sentora.com/research/dashboards/cdp-protocols
- https://www.rapidinnovation.io/post/defi-revolution-complete-guide-decentralized-finance

## Ethereum VM

|  Platform                              |  Core Mechanism                         |  Notes                                                                                     |
|----------------------------------------|-----------------------------------------|--------------------------------------------------------------------------------------------|
|  **Sky Protocol/MakerDAO**            | Classic crypto-backed CDPs issuingDAI   |  Overcollateralized vaults using ETH, USDC, RWAs; fully decentralized governance     |
|  **Aave**                              | Overcollateralized borrowing & lending  |  Leading non-custodial lending protocol, supports flash loans, stable/variable rates |
|  **Compound Finance**                  | Algorithmic money markets               |  Automatically adjusting interest rates; base for many other lending markets         |
|  **Liquity**                           | ETH-backed loans issuingLUSD            |  Zero-interest loans, fully immutable, no governance                                 |
|  **Spark Protocol** (Maker Ecosystem)  | MakerDAO subprotocol using DAI          |  Institutional lending branch built on Maker’s infrastructure                        |
|  **Silo Finance**                      | Isolated lending markets                |  Independent siloed risk per asset; allows CDP functionality per-token               |
|  **Hundred Finance**                   | Multi-chain lending hub                 |  Uses veHND mechanics; fork of Compound; cross-chain CDP features                    |
|  **Instadapp Lite**                    | Smart account for CDPs                  |  Automated vault management on Maker, Aave, Compound                                 |
|  **Venus Protocol**                    | Synthetic CDPs issuingVAI stablecoin    |  Combines Compound-style markets with stablecoin minting                             |
|  **Radiant Capital**                  | Unified cross-chain money market        |  Built on LayerZero tech for omni-chain liquidity; collateralized lending            |

## Solana

|**Platform**           |  **Key Features**                                                                       |  **Notes**                                              |                                      
|-----------------------|-----------------------------------------------------------------------------------------|-------------------------------------------------------- |
| **Kamino Finance**    |  Dominant lending/CDP platform, concentrated liquidity, high LTV, Solana native assets  |  Largest TVL; seamless DEX integration                  |
| **Save Finance**      |  No repayment deadline loans, 129+ collateral options, audited, SAVE token              |  Rebranded from Solend, open source, robust audits      |
| **Marinade Finance**  |  Liquid staking CDPs, receive mSOL for DeFi use, large TVL                              |  Top liquid staking provider, mSOL as DeFi collateral   |
| **Jet Protocol**      |  Tight collateral ratios, dynamic pricing, cross-chain modules                          |  Emphasizes governance and advanced position management |
| **Larix**             |  Wide collateral support, risk modeling, NFT/metaverse assets                           |  First Solana metaverse lending protocol                |
| **Apricot Finance**   |  Leveraged yield farming, cross-farm modules, auto-deleveraging                         |  DeFi for advanced and casual users                     |
| **Port Finance**      |  Variable rates, money market focus, flash loans                                        |  Supports a range of secured lending                    |
| **Parrot**            |  Stablecoin minting against collateral, DeFi optimization                               |  DeFi composability, stablecoin CDPs                    |
| **Tulip**             |  Yield aggregation, leveraged yield strategies                                          |  Lending with auto-compounding/Yield farming            |
| **Hubble Protocol**   |  Borrow USDH stablecoin, overcollateralized, dynamic liquidations                       |  Hubble’s CDP vaults are optimized for Solana           |

##A Cosmos

|  Platform            |  Chain                     |  Core Mechanism                                   |  Notes                                                                       |
|----------------------|----------------------------|---------------------------------------------------|------------------------------------------------------------------------------|
|  **Noble**           |  Cosmos Hub zone           |  Fiat and RWA-backed stablecoin issuance          |  Native home ofUSDC, USDY, USDN; serves as Cosmos’s interchain issuance layer|
|  **Shade Protocol**  |  Secret Network            |  Overcollateralized, privacy-preserving CDP       |  IssuesSILK, a basket-pegged stablecoin collateralized by BTC, ETH, and ATOM |
|  **Ondo Finance**    |  Noble / Cosmos SDK Chain  |  RWA-based CDPs with tokenized Treasuries         |  IssuesUSDY(yield-bearing) andOUSG, used as DeFi collateral                  |
|  **Pryzm**           |  Cosmos                    |  Yield-bearing stablecoin bridge                  |  Connects to MakerDAO’sSkystablecoin (sUSDS) through IBC Eureka              |
|  **Kava**            |  Kava Chain                |  CDP and stablecoin (USDt-native)                 |  Long-running Cosmos-native CDP issuing USDX, moving toward USDT-CDPs        |
|  **KUJI (Kujira)**   |  Kujira                    |  Collateralized lending and liquidation markets   |  Offers overcollateralized loans, liquidation auctions, and $USK stablecoin  |
|  **Mars Protocol**   |  Osmosis / Neutron         |  Credit protocol with variable collateralization  |  Supports under- and overcollateralized loans across multiple IBC chains     |
|  **Comdex**          |  Comdex Chain              |  Institutional RWA lending                        |  Allows creation of synthetic credit via tokenized commodities and treasuries|
|  **Agoric**          |  Agoric Chain              |  Smart CDP model with ERTP framework              |  Enabling Javascript-based smart contracts for stable tokens and lending     |
|  **Mantra**          |  Cosmos + EVM compatible   |  Regulated RWA financing and CDPs                 |  Integrates KYC-based DeFi for institutions using compliance-grade CDPs      |
