# Basic Sample Hardhat Project

This project demonstrates a basic Hardhat use case. It comes with a sample contract, a test for that contract, a sample script that deploys that contract, and an example of a task implementation, which simply lists the available accounts.

Try running some of the following tasks:

```shell
npx hardhat accounts
npx hardhat compile
npx hardhat clean
npx hardhat test
npx hardhat node
node scripts/sample-script.js
npx hardhat help
```
deploy contract via remix
deployed to mumbai test
0xc58e3fFF18eDB59d05074676ee4Ce1ddF276611d

deploy the files, json and metadata to moralis (install moralis-admin-cli 1st)
```shell
cd moralis_host
moralis-admin-cli deploy   
```      

after successfull deploy, capture the url returned in response. And set as a arg for 
```shell
constructor() ERC1155("")
```
