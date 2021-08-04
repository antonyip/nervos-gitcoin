# Bounty
https://gitcoin.co/issue/nervosnetwork/grants/4/100026210

# Deliverables
A screenshot of the console output immediately after you have successfully issued a smart contract call.
![image](https://user-images.githubusercontent.com/9086733/128202964-bb9a5f94-6525-4faf-9207-206bcf694c51.png)

The transaction hash from the console output (in text format).  
```0x2305c37a123d2176d3f7fe58574464486a0c5a346c582850c46ae7f93ca47282```
  
The contract address that you called (in text format).  
```0x3d2747511d514F820c1D4Eb797F154bD88c4C388```

The ABI for contract you made a call on (in text format).
```
const CONTRACT_ABI = [
  {
    "inputs": [],
    "stateMutability": "payable",
    "type": "constructor"
  },
  {
    "inputs": [
      {
        "internalType": "uint256",
        "name": "x",
        "type": "uint256"
      }
    ],
    "name": "set",
    "outputs": [],
    "stateMutability": "payable",
    "type": "function"
  },
  {
    "inputs": [],
    "name": "get",
    "outputs": [
      {
        "internalType": "uint256",
        "name": "",
        "type": "uint256"
      }
    ],
    "stateMutability": "view",
    "type": "function"
  }];
  ```
