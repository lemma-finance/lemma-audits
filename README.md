# audits
Audits and known issues for lemma core contracts

## Known-issues
- [calculateMintingAsset](https://github.com/lemma-finance/basis-trading-stablecoin/blob/master/contracts/wrappers/PerpLemmaCommon.sol#L647)
  - This is not enforced anymore. A Governance [transaction](https://optimistic.etherscan.io/tx/0x2b4f730d121e77310a67b382640f72eec109a3419b1bbcfad0f819ee2a06f003) was made to call this function and set the values appropiately.
