
# Add custom image:
## Requirements
- name of the file in lowercase: `contract_address.png`. Ex: `0xd26114cd6ee289accf82350c8d8487fedb8a0c07.png`
- format: `PNG`
- size: `256px by 256px`

## Steps
1) Press on `Fork` in the top right corner.
2) Upload an image in `ethereum/` or `irchain/` folder on your own fork and commit changes.
```
Directory of token images for ERC20 contracts
Ethereum/IrChain Based Network
	`irchain-chainID.png`
	`ethereum-chainID.png`
Example:
	`irchain-1.png`
	`ethereum-1.png`

ERC20 Token
	`contract_address.png`
Example:
	`0xd26114cd6ee289accf82350c8d8487fedb8a0c07.png`
	`Cd26114cd6ee289accf82350c8d8487fedb8a0c07.png`
```

3) Press on `New Pull Request` on your own fork page and submit it!



## How to Use It? (For Developers)
Base URL:
```js
https://raw.githubusercontent.com/icToken/ic-icons/master/<ethereum|irchain>/<contract_address>.png
```
Example:
```js
https://raw.githubusercontent.com/icToken/ic-icons/master/irchain/0x91a55ea8e0734e5190339f34b5ce2134c7831e16.png
```

## Used in Applications
- [icToken](https://dapp.irchain.io/token/) - iOS and Android 
