# AhojSynth
Ahoj.Synth is a synthetic asset protocol running on Avalanche

This repository is a collection of smart contracts that implement the Ahoj.Swap protocol on Avalanche.

Ahoj is a Czech word from English ahoy. The word Ahoj is used to say *Hello* (informal greeting said when meeting someone) or inclusive to say *Bye* (informal farewell).

## Table of Contents

- [Install](#install)
- [Testing](#testing)
- [Contribute](#contribute)
- [License](#license)


## Install

```bash
# Install project dependencies
npm install

# Install ethereum local blockchain(s) and associated dependencies
npx setup-local-chains
```

## Testing

``` bash
# You can use the following command to start a local blockchain instance
npx start-chain [ganacheUnitTest|gethUnitTest]

# Run all unit tests
npm test

# Run unit tests in isolation
npx truffle --network ganacheUnitTest test test/unit/ahoj.js
```

## Contribute

To report bugs within this package, create an issue in this repository.
For security issues, please contact hello@bayro.io.
When submitting code ensure that it is free of lint errors and has 100% test coverage.

``` bash
# Lint code
npm run lint

# View code coverage
npm run coverage
```

## License

[GNU General Public License v3.0 (c) 2020 Bayro](./LICENSE)
