# How to use
0. compile source contracts:
```
poa-parity

1. create .env file
```bash
DEPLOYMENT_ACCOUNT_ADDRESS=0xb8988b690910913c97a090c3a6f80fad8b3a4683
DEPLOYMENT_ACCOUNT_PRIVATE_KEY=67..14
DEPLOYMENT_GAS_LIMIT=4000000
DEPLOYMENT_GAS_PRICE=10
GET_RECEIPT_INTERVAL_IN_MILLISECONDS=3000

HOME_RPC_URL=https://sokol.poa.network
HOME_OWNER_MULTISIG=0x
HOME_UPGRADEABLE_ADMIN_VALIDATORS=0x
HOME_UPGRADEABLE_ADMIN_BRIDGE=0x
HOME_DAILY_LIMIT=30000000000000000000000000
HOME_MAX_AMOUNT_PER_TX=1500000000000000000000000
HOME_MIN_AMOUNT_PER_TX=500000000000000000
HOME_REQUIRED_BLOCK_CONFIRMATIONS=1
HOME_GAS_PRICE=1

FOREIGN_RPC_URL=https://sokol.poa.network
FOREIGN_OWNER_MULTISIG=0x
FOREIGN_UPGRADEABLE_ADMIN_VALIDATORS=0x
FOREIGN_UPGRADEABLE_ADMIN_BRIDGE=0x
FOREIGN_DAILY_LIMIT=15000000000000000000000000
FOREIGN_MAX_AMOUNT_PER_TX=750000000000000000000000
FOREIGN_MIN_AMOUNT_PER_TX=500000000000000000
FOREIGN_REQUIRED_BLOCK_CONFIRMATIONS=8
FOREIGN_GAS_PRICE=10

REQUIRED_NUMBER_OF_VALIDATORS=1
VALIDATORS="0x 0x 0x"



```
2.  Run `node deploy.js`
OR
2. Compile sources: `npm run compile`
3. run `./build/deploy-macos`




