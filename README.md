# Liquidity mining

This repository contains the contracts to manage the liquidity mining.

The following assumes the use of `node@>=10`.

## Install Dependencies

`yarn`

## Compile Contracts

`yarn compile`

## Generate Merkle Tree

`yarn generate-merkle-root --input airdrop.json > merkle.json`

The [airdrop.json](https://github.com/materia-dex/materia-retroqueries/blob/master/results/airdrop.json) can be generated using the proper script in [materia-retroqueries](https://github.com/materia-dex/materia-retroqueries).