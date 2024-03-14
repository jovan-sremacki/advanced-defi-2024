# advanced-defi-2024

## Goals

- Be able to integrate a simple dapp into another defi protocol
- Understand the fundamentals of protocols
- TODO: Simple apps for each protocol

## Install

- foundry
- python?

## Topics

// TODO: rename videos

// TODO: one click download cheatsheet

// TODO: update sol to 0.8.24

- [ ] Syllabus
- [ ] AMM

  - [ ] What is an AMM?
  - [ ] AMM vs orderbook
  - [ ] Different AMM Equations
  - [ ] Uniswap v2
    - [ ] Math overview, graph and examples
    - [ ] Contracts overview
    - [ ] Swap
      - [ ] Swap math, example and graph
      - [ ] Contract calls diagram
      - [ ] Code walkthrough
        - [ ] Periphery and Core
        - [ ] swapExactTokensForTokens
          - [ ] getAmountsOut
          - [ ] getAmountsOut fork
          - [ ] getAmountsOut example
        - [ ] swapTokensForExactTokens
          - [ ] getAmountsIn
          - [ ] getAmountsIn fork
          - [ ] getAmountsIn example
      - [ ] Code exercises
      - [ ] Code solutions
      - [ ] Spot price graph
      - [ ] Spot price math
      - [ ] Slippage
    - [ ] Create pool
      - [ ] Code walkthrough
      - [ ] Code exercises
      - [ ] Code solutions
    - [ ] Add liquidity
      - [ ] Pool shares math - mint and burn
      - [ ] Add liquidity math, example and graph
      - [ ] Contract calls diagram
      - [ ] Code walkthrough
        - [ ] addLiquidity
        - [ ] mint
      - [ ] Code exercises
      - [ ] Code solutions
    - [ ] Remove liquidity
      - [ ] Remove liquidity graph
      - [ ] Remove liquidity math
      - [ ] Contract calls diagram
      - [ ] Code walkthrough
      - [ ] Code exercises
      - [ ] Code solutions
    - [ ] Flash swap
      - [ ] Flash swap fee math
      - [ ] Contract calls diagram
      - [ ] Code walkthrough
      - [ ] Code exercises
      - [ ] Code solutions
    - [ ] TWAP
      - [ ] Spot price manipulation
      - [ ] TWAP math
        - [ ] Intro
        - [ ] Cumulative price
        - [ ] Example
        - [ ] TWAP approximation to current time
        - [ ] Misconception
      - [ ] Code walkthrough
      - [ ] Code exercises
      - [ ] Code solutions
    - [ ] sandwich 🤔
    - [ ] Application - Flash swap arbitrage
      - [ ] Intro
        - [ ] arbitrage, flash swap -> swap -> swap)
        - [ ] flash swap -> swap
      - [ ] Exercise
      - [ ] Solution 1
      - [ ] Solution 2
      - [ ] Optimal amount in math 🤔
  - [ ] Uniswap v3
    - [ ] Math
    - [ ] Contract overview
    - [ ] Swap
    - [ ] Add / remove liquidity
      - [ ] JIT liquidity
    - [ ] Flash swap
    - [ ] TWAP
  - [ ] Curve v1
    - [ ] Math
    - [ ] Swap
    - [ ] Add / remove liquidity
    - [ ] TWAP🤔
  - [ ] Curve v2🤔
    - [ ] Math
  - [ ] dy / dx = dfdx / dfdy 🤔
  - [ ] Summary

- [ ] MEV
  - [ ] Front run, back run and sandwich examples
  - [ ] Flashbots RPC example
  - [ ] MEV sandwicsh uni v2 🤔
  - [ ] Summary
- [ ] Price oracle ✅
  - [ ] Chainlink
- [ ] Stablecoin ✅
  - [ ] DAI
    - [ ] Overview
    - [ ] CDP and vaults
    - [ ] Math (wad, ray, rad)
    - [ ] Debt math
    - [ ] Contract overview
    - [ ] Add collateral
    - [ ] Borrow
    - [ ] Repay
    - [ ] Liquidation, math and auction
    - [ ] Debt auction
    - [ ] Surplus auction
    - [ ] DSR (math)
    - [ ] PSM
    - [ ] Flash
    - [ ] Flash mint DAI -> Sell DAI for USDC on Uniswap -> Sell USDC to PSM -> Repay flash loan
    - [ ] What can we do with DAI and Maker protocol?🤔
    - [ ] Leverage🤔
    - [ ] Summary
- [ ] Lending
  - [ ] AAVE 🚧
    - [ ] supply
    - [ ] borrow
    - [ ] repay
    - [ ] withdraw
    - [ ] flash loan
    - [ ] liquidation
    - [ ] GHO 🤔
    - [ ] portal 🤔
    - [ ] stake AAVE 🤔
    - [ ] govenance 🤔
    - [ ] apps -> flash loan, farm gov tokens, leverage, short 🤔
  - [ ] Compound 🤔
  - [ ] Flash loan
  - [ ] Rebase tokens
  - [ ] Summary
- [ ] Liquid staking 🚧
  - [ ]Lido
  - [ ]Rocket pool 🤔

## TODOs

- [ ] Compound
- [ ] TWAMM
- [ ] AAVE GHO
- [ ] Curve stablecoin
- [ ] Curve VE gauge🤔 (liquidity -> better price for users -> more trade -> more fee -> more liquidity)?
- [ ] RAI
- [ ] Dex aggregator (CowSwap, ParaSwap)

- How to cover theses topics?
  - Algorithms used in DeFi
    - AMM
    - Vault
    - Staking rewards (discrete and time based)
    - DAI interest rate
    - Dutch auction
    - English and Dutch auction
- DEX agg - cow swap, paraswap?

## Resources

- cyfrin updraft
- https://defillama.com/
- https://www.youtube.com/@blockchain-web3moocs635/playlists

[Whitepapers](./whitepapers)

#### Uniswap

- [Uniswap](https://uniswap.org/)

#### Aave

- [Aave](https://aave.com/)
- [Aave Unleashed](https://calnix.gitbook.io/aave-unleashed/)

- [Curve](https://resources.curve.fi/)

- [Aave V3 Made Crystal Clear](https://www.youtube.com/watch?v=UzuZp3Q3xg0)
