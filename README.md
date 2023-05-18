# FakeSpot
Final Year Project Fake Product Identification

Download This:

- Metamask
- Ganache
- NodeJs

## How To Run
Install node packages using
```
npm install
```
```
truffle compile
```
- In Ganache 
  - Create New Workspace
  - Add truffle-config.js file from the project folder in truffle project.
  - To get free test ethers copy the private key and make new network in the metamask and paste your private key there.

- Add new test network using  
  - NETWORK ID (i.e. 5777 ,from Ganache Server settings) 
  - RPC SERVER (i.e HTTP://127.0.0.1:8545 ,from Ganache Server settings)
  - CHAIN CODE (i.e. 1337)
```
truffle migrate
```
```
npm run dev
```
