# Gitcoin-7)Port An Existing Ethereum DApp To Polyjuice

### 1- Screenshot and video of the DApp

- <a href="https://youtu.be/CjBnqjGgwRk"> VIDEO </a>
<img src="https://github.com/tfthecoder/Nervos-hackathon/blob/master/task-07/ss.png" />

### 2- Source Code

<a href="https://github.com/tfthecoder/Name-Storage-DApp-Nervos"> Github Link </a>

### 3- Contract Details

Deployed Contract Address: ```0xbEB3E1A1c443e2c740155988185A532B100a5a7b```

Transaction hash: ```0x02116e2bb1bda9be0498a6bcd38422d2a4f2c38d10e9b66a55c7cffee86fc2ff```

ABI

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
