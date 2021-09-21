# tezos-ide

A simple IDE to write, test, compile and deploy Tezos smart contracts. Leveraging [Taquito](https://tezostaquito.io/) and [SmartPy](https://smartpy.io/). 

## Setup

1. Install SmartPy.

```bash
$ sh <(curl -s https://smartpy.io/cli/install.sh)
```

2. Install Node dependencies. 

```bash
$ npm i
```

## Compile/test contracts 

```bash
$ npm run compile-contracts <contract_name>
```

## Deploy contracts 

```bash
$ npm run deploy-contracts
```

_See `.env.template` for required environment variables._