# N3R Yield Source Specification

The Yield Source Interface is defined in the [IYieldSource.sol](./contracts/IYieldSource.sol) file.

Keep in mind:

- All deposits are denominated in the `depositToken()` ERC20.
- The `balanceOfToken(address)` function is similar to the Aave aToken, in that the balance must always increase.
