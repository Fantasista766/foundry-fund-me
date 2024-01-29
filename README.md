# Usage

## Deploy:

```
forge script script/DeployFundMe.s.sol
```

## Testing


```
forge test
```

or 

```
forge test --match-test testFunctionName
```

### Test Coverage

```
forge coverage
```

# Deployment to a testnet or mainnet

Deploy

```
forge script script/DeployFundMe.s.sol --rpc-url $SEPOLIA_RPC_URL --private-key $PRIVATE_KEY --broadcast --verify --etherscan-api-key $ETHERSCAN_API_KEY
```

## Scripts

```
forge script script/Interactions.s.sol --rpc-url sepolia  --private-key $PRIVATE_KEY  --broadcast
```

## Estimate gas

You can estimate how much gas things cost by running:

```
forge snapshot
```

And you'll see an output file called `.gas-snapshot`


# Formatting

To run code formatting:
```
forge fmt
```