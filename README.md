# LFI Contracts

[BSCswap Stable](https://stable.bscswap.com), with integration of [LOA DeFi](https://loaprotocol.io/).

## Contracts

* [`BAI`](BAI.sol): Bai Stablecoin, Wraps supported stablecoins into the form of LP token
* [`DepositLFI`](DepositLFI.sol): Depositor contract, used to wrap underlying tokens prior to depositing them into the pool.
* [`StableSwapLFI`](StableSwapLFI.sol): BSCswap Stable AMM contract
* [`LFIVault`](LFIVault.sol): Lent Tokens, connected strategy contract could be upgraded by the Timelock contract
* [`LFIStrategy`](LFIStrategy.sol): Vault connecting Lent tokens and Lending protocols, wraps ForTube token in form of utility token (Lent Tokens)

## Deployments

* [`BAI`](BAI.sol): [0xaA8012a0Ea627767545a8E435C2A2BD51f60173D](https://bscscan.com/address/0xaA8012a0Ea627767545a8E435C2A2BD51f60173D)
* [`DepositLFI`](DepositLFI.sol): [0x39c56Bda66dc8c2E17FeB350DC504E12b98ABDe2](https://bscscan.com/address/0x39c56Bda66dc8c2E17FeB350DC504E12b98ABDe2)
* [`StableSwapLFI`](StableSwapLFI.sol): [0x15EA853B07382Dc2Ac8F91933446ac459737E4a6](https://bscscan.com/address/0x15EA853B07382Dc2Ac8F91933446ac459737E4a6)
* [`LFIVault`](LFIVault.sol): [0x2fD8AD2546db48Cc0666D6F1a12AbA3cA056Fca8](https://bscscan.com/address/0x2fD8AD2546db48Cc0666D6F1a12AbA3cA056Fca8)
* [`LFIStrategy`](LFIStrategy.sol): [0x80b56fD66F067b4D25700104EA61449e25FD238e](https://bscscan.com/address/0x80b56fD66F067b4D25700104EA61449e25FD238e)
* [`Timelock`](Timelock.sol): [0xf54d53D840747C71573fC42e0dFd9478332f8005](https://bscscan.com/address/0xf54d53d840747c71573fc42e0dfd9478332f8005)

## Stablecoins

BSCswap Stable supports swaps between the following stablecoins:

### Wrapped

* `LBUSD`: [0x2fD8AD2546db48Cc0666D6F1a12AbA3cA056Fca8](https://bscscan.com/address/0x2fD8AD2546db48Cc0666D6F1a12AbA3cA056Fca8)
* `LUSDT`: [0x7859876FcEeA9D085Db181f9b1aFfC2f70036863](https://bscscan.com/address/0x7859876FcEeA9D085Db181f9b1aFfC2f70036863)
* `LDAI`: [0x322B4046BE800B55B1c314162797CE416E569994](https://bscscan.com/address/0x322B4046BE800B55B1c314162797CE416E569994)

### Underlying

* `BUSD`: [0xe9e7CEA3DedcA5984780Bafc599bD69ADd087D56](https://bscscan.com/token/0xe9e7CEA3DedcA5984780Bafc599bD69ADd087D56)
* `USDT`: [0x55d398326f99059fF775485246999027B3197955](https://bscscan.com/token/0x55d398326f99059fF775485246999027B3197955)
* `DAI`: [0x1AF3F329e8BE154074D8769D1FFa4eE058B1DBc3](https://bscscan.com/address/0x1AF3F329e8BE154074D8769D1FFa4eE058B1DBc3)
