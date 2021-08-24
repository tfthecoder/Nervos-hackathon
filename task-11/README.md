# Gitcoin: 11) Use A Tron Wallet To Execute A Smart Contract Call


### 1-) A screenshot of the accounts you created

<img src="https://github.com/tfthecoder/Nervos-hackathon/blob/master/task-11/acc-list.jpg" />


### 2-) A link to the Layer 1 address you funded on the Testnet Explorer

<a href="https://explorer.nervos.org/aggron/address/ckt1qyqyrxgkcnguznfk6feqe8lwqj2cf4uu5xgqvlwaf8" > Explorer link </a>

### 3-) A screenshot of the console output immediately after you have successfully submitted a CKByte deposit to your Tron account on Layer 2

<img src="https://github.com/tfthecoder/Nervos-hackathon/blob/master/task-11/deposit.png" />

### 4-) A screenshot of the console output immediately after you have successfully issued a smart contract calls on Layer 2

<img src="https://github.com/tfthecoder/Nervos-hackathon/blob/master/task-11/contract-call.png" />

### 5) The transaction hash of the "Contract call" from the console output

```bash
0x218aca8d9e5c35a2023928bba62e636f3f2f69f16a529efeeb73aabb0f585f81
```
### 6) The contract address that you called

```bash
0xbEB3E1A1c443e2c740155988185A532B100a5a7b
```

### 7) The ABI for contract you made a call on

```javascript
[
    {
      "inputs": [],
      "stateMutability": "nonpayable",
      "type": "constructor"
    },
    {
      "inputs": [
        {
          "internalType": "uint256",
          "name": "",
          "type": "uint256"
        }
      ],
      "name": "names",
      "outputs": [
        {
          "internalType": "uint256",
          "name": "id",
          "type": "uint256"
        },
        {
          "internalType": "string",
          "name": "name",
          "type": "string"
        }
      ],
      "stateMutability": "view",
      "type": "function"
    },
    {
      "inputs": [],
      "name": "totalName",
      "outputs": [
        {
          "internalType": "uint256",
          "name": "",
          "type": "uint256"
        }
      ],
      "stateMutability": "view",
      "type": "function"
    },
    {
      "inputs": [
        {
          "internalType": "string",
          "name": "_name",
          "type": "string"
        }
      ],
      "name": "addName",
      "outputs": [],
      "stateMutability": "nonpayable",
      "type": "function"
    }
  ]

```

### 8) Your Tron address

```bash
TGJ33amFyNRnSSAutveAjfAL9KvfTd5Vgx
```
