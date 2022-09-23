# 3f-web3-eth-iban

This is a sub package of [3f-web3.js]

This is the IBAN package to be used in the `web3-eth` package.

## Installation

### Node.js

```bash
npm install 3f-web3-eth-iban
```
## Usage

```js
const Web3EthIban = require('3f-web3-eth-iban');

const iban = new Web3EthIban('XE75JRZCTTLBSYEQBGAS7GID8DKR7QY0QA3');
iban.toAddress() > '0xa94f5374Fce5edBC8E2a8697C15331677e6EbF0B';
```


## Types

All the TypeScript typings are placed in the `types` folder.


