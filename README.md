# Project Goal is to develop a liquidity mining protocol for DEX

In this project we will develop smartcontracts for liquidity mining on Uniswap, balancer, Curve, and others with various strategies that yields better return. Our goal is to optimize the strategies. 

## Steps:
    1. Get Current rate and APY for each currency pair from DEX exchanges
    2. Develop a weight matrix for risk and return characteristics of these liquidity 
    3. With given weight stake currencies in these pools to have return
    4. Check in regular interval about the risk return changes
    5. Update the weight matrix and rebalance the stake in pools
    

## Common Commands
```shell
npx hardhat accounts
npx hardhat compile
npx hardhat clean
npx hardhat test
npx hardhat node
npx hardhat help
REPORT_GAS=true npx hardhat test
npx hardhat coverage
npx hardhat run scripts/deploy.js
node scripts/deploy.js
npx eslint '**/*.js'
npx eslint '**/*.js' --fix
npx prettier '**/*.{json,sol,md}' --check
npx prettier '**/*.{json,sol,md}' --write
npx solhint 'contracts/**/*.sol'
npx solhint 'contracts/**/*.sol' --fix
```

```shell
hardhat run --network ropsten scripts/deploy.js
```

Then, copy the deployment address and paste it in to replace `DEPLOYED_CONTRACT_ADDRESS` in this command:

```shell
npx hardhat verify --network ropsten DEPLOYED_CONTRACT_ADDRESS "Hello, Hardhat!"
```
