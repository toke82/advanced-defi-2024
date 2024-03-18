# advanced-defi-2024

## Install

```shell
# Install foundry
curl -L https://foundry.paradigm.xyz | bash
foundryup
```

## Exercises and solutions

```shell
cd foundry
forge build
```

## Topics

- [ ] Syllabus
- [ ] AMM
  - [ ] Intro
    - [ ] 1. What is an AMM?
    - [ ] 2. AMM vs orderbook
    - [ ] 3. Different AMM Equations
  - [ ] [Uniswap V2](./topics/amm/uniswap-v2/README.md)
    - [ ] 1. Math overview, graph and examples
    - [ ] 2 Contracts overview
    - [ ] Swap
      - [ ] 3. Swap math
      - [ ] 4. Swap fee math
      - [ ] 5. Contract calls diagram
      - [ ] Code walkthrough
        - [ ] 6. Periphery and core repositories
        - [ ] 7. swapExactTokensForTokens
          - [ ] 8. getAmountsOut
          - [ ] 9. getAmountsOut fork
          - [ ] 10. getAmountsOut example
        - [ ] 11. swapTokensForExactTokens
          - [ ] 12. getAmountsIn
          - [ ] 13. getAmountsIn fork
          - [ ] 14. getAmountsIn example
        - [ ] 15. pair.swap
      - [ ] 16. Code exercise 1
      - [ ] 17. Code solution 1
      - [ ] 18. Code exercise 2
      - [ ] 10. Code solution 2
      - [ ] 20. Spot price graph
      - [ ] 21. Spot price math
      - [ ] 22. Slippage
    - [ ] Create pool
      - [ ] 23. Code walkthrough
      - [ ] 24. Code exercise
      - [ ] 25. Code solution
    - [ ] Add liquidity
      - [ ] 26. Pool shares intro
        - [ ] 27. Pool shares mint math
        - [ ] 28. Pool shares mint math example
        - [ ] 29. Pool shares burn
        - [ ] 30. Pool shares burn math
        - [ ] 31. Pool shares burn math example
      - [ ] 32. Add liquidity graph
      - [ ] 33. Add liquidity math
      - [ ] 34. Add liquidity pool shares math intro
        - [ ] 35. Liquidity functions
        - [ ] 36. Liquidity functions - sqrt
        - [ ] 37. Liquidity functions - 2x
        - [ ] 38. Summary
      - [ ] 39. Contract calls diagram
      - [ ] Code walkthrough
        - [ ] 40. addLiquidity
        - [ ] 41. mint
      - [ ] 42. Code exercise
      - [ ] 43. Code solution
    - [ ] Remove liquidity
      - [ ] 44. Remove liquidity graph
      - [ ] Remove liquidity math
        - [ ] 45. How many dx and dy to remove?
        - [ ] 46. Pool shares intro
        - [ ] 47. Liquidity functions
        - [ ] 48. Liquidity delta with liquidity function = sqrt
      - [ ] 49. Contract calls diagram
      - [ ] Code walkthrough
        - [ ] 50. removeLiquidity
        - [ ] 51. burn
      - [ ] 52. Code exercise
      - [ ] 53. Code solution
    - [ ] Flash swap
      - [ ] 54. Flash swap fee math
      - [ ] 55. Contract calls diagram
      - [ ] 56. Code walkthrough
      - [ ] 57. Code exercise
      - [ ] 58. Code solution
    - [ ] TWAP
      - [ ] 59. Spot price manipulation
      - [ ] TWAP math
        - [ ] 60. Intro
        - [ ] 61. Cumulative price
        - [ ] 62. Example
        - [ ] 63. TWAP approximation to current time
        - [ ] 64. Misconception
      - [ ] 65. Code walkthrough
      - [ ] 66. Code exercise
      - [ ] 67. Code solution
    - [ ] Application - Flash swap arbitrage
      - [ ] Intro
        - [ ] 68. arbitrage, flash swap -> swap -> swap)
        - [ ] 69. flash swap -> swap
      - [ ] 70. Exercise 1
      - [ ] 71. Solution 1
      - [ ] 72. Exercise 2
      - [ ] 73. Solution 2
  - [ ] Uniswap v3
  - [ ] Curve v1
  - [ ] Curve v2
- [ ] MEV
- [ ] Price oracle - Chainlink
- [ ] Stablecoin - DAI
- [ ] Lending - AAVE v3

## Resources

- https://updraft.cyfrin.io/
- https://defillama.com/
- https://www.youtube.com/@blockchain-web3moocs635/playlists

[Whitepapers](./whitepapers)
