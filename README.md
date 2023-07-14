# ETH-AVAX-Mod1
# Solidity Contract: checkRequireRevertAssert

This Solidity smart contract demonstrates the usage of `require`, `revert`, and `assert` statements. It provides three functions that showcase different ways to handle conditions in Solidity.

## Installation

To interact with this contract, you will need the following:

- Solidity compiler
- Ethereum development environment (e.g., Remix, Truffle, Hardhat)

## Usage

1. Clone the repository or create a new Solidity file and copy the contract code.
2. Compile the contract using the Solidity compiler with a version that is compatible with `pragma solidity ^0.8.8`.
3. Deploy the contract to a local or test Ethereum network.
4. Interact with the contract by calling the following functions:

### `checkRequire(uint256 _x)`

This function checks the value of `_x` and uses the `require` statement to ensure that `_x` is less than 30. If the condition is not met, it throws an error message and reverts all changes made in the function. Otherwise, it sets `num` to 50.

### `checkRevert(uint256 _x)`

This function checks the value of `_x` and uses an `if` statement to check if `_x` is greater than 30. If the condition is true, it throws an error message and reverts all changes made in the function. Otherwise, it sets `num` to 50.

### `checkAssert(uint256 _x)`

This function checks the value of `_x` and uses the `assert` statement to verify that `_x` is less than 30. If the condition is false, it throws an error and reverts all changes made in the function. Otherwise, it sets `num` to 50.

## Authors
Vaishnavi Arora

## License
This contract is licensed under the MIT License. SPDX-License-Identifier: MIT.


