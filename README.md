# ETH-Beginner
### DESCRIPTION

Here in this code snippet we are going to understand how to work with Solidity and creat BURN & MINT functions.

### GETTING STARTED
- Remix Editor

### Burn & Mint Functions

```
function mint(address addr, uint amount) external {
        balances[addr] += amount;
        totalSupply += amount;
    }

    function burn(address addr, uint amount) external {
        if(balances[addr]>=amount && totalSupply > amount){
            balances[addr] -= amount;
            totalSupply -= amount;
        }
```

### Authors
- Sabhye Gulati
