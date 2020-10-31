# LFI Contracts

[BSCswap Stable](https://stable.bscswap.com), with integration of [LOA DeFi](https://loaprotocol.io/).

## Contracts

* [`DepositLFI`](DepositLFI.sol): Depositor contract, used to wrap underlying tokens prior to depositing them into the pool.
* [`StableSwapLFI`](StableSwapLFI.sol): BSCswap Stable AMM contract

## Deployments

* [`BAI`](BAI.sol): [0x2976748a05Ae49294EBb02e9CEf0d9D8b1b3B8Cd](https://bscscan.com/address/0x2976748a05Ae49294EBb02e9CEf0d9D8b1b3B8Cd)
* [`DepositLFI`](DepositLFI.sol): [0x2bc0E6c5F0279e53075486d0aA714C58767D8c22](https://bscscan.com/address/0x2bc0E6c5F0279e53075486d0aA714C58767D8c22)
* [`StableSwapLFI`](StableSwapLFI.sol): [0xB3F7F9eFa4e4Da44BA4DCd1937673795f491a540](https://bscscan.com/address/0xB3F7F9eFa4e4Da44BA4DCd1937673795f491a540)
* [`LFIVault`](LFIVault.sol): [0xD6De1Dfd71321f26800d048c81Ce1E3944b97a5F](https://bscscan.com/address/0xD6De1Dfd71321f26800d048c81Ce1E3944b97a5F)]
* [`StrategyFortube`](StrategyFortube.sol): [0x118eb846A2ACc29E09fD4CdA97544109044793c9](https://bscscan.com/address/0x118eb846A2ACc29E09fD4CdA97544109044793c9)

## Stablecoins

BSCswap Stable supports swaps between the following stablecoins:

### Wrapped

* `LBUSD`: [0xD6De1Dfd71321f26800d048c81Ce1E3944b97a5F](https://bscscan.com/address/0xD6De1Dfd71321f26800d048c81Ce1E3944b97a5F)
* `LUSDT`: [0xb43d42C085A504E4633975190395b4412d0B5c5D](https://bscscan.com/address/0xb43d42C085A504E4633975190395b4412d0B5c5D)
* `LDAI`: [0x71FE4e07a87bA7ef4c8c1C84793EAb9D4A3868Fd](https://bscscan.com/address/0x71FE4e07a87bA7ef4c8c1C84793EAb9D4A3868Fd)

### Underlying

* `BUSD`: [0xe9e7CEA3DedcA5984780Bafc599bD69ADd087D56](https://bscscan.com/token/0xe9e7CEA3DedcA5984780Bafc599bD69ADd087D56)
* `USDT`: [0x55d398326f99059fF775485246999027B3197955](https://bscscan.com/token/0x55d398326f99059fF775485246999027B3197955)
* `DAI`: [0x1AF3F329e8BE154074D8769D1FFa4eE058B1DBc3](https://bscscan.com/address/0x1AF3F329e8BE154074D8769D1FFa4eE058B1DBc3)
