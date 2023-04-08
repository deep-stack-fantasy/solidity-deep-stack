# Solidity mod: Deep Stack Fantasy

## Objective
- Get rid of `stack too deep` errors! Increase the number of allowed variables by 16 times.
- Generate modified EVM bytecodes that can be run by [go-ethereum-deep-stack](https://github.com/deep-stack-fantasy/go-ethereum-deep-stack). Suitable for private blockchains.

## Working Progress
- [x] Generate new `DupE` and `SwapE` EVM operations.
- [x] Extend maximum stack access range from 16 to 255.
- [ ] Solve the invalid jump issue.
- [ ] Reformat codes and rebase commit messages.
- [ ] Support optimizations.
- [ ] Support unit tests.

## License
GPL v3
