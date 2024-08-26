# Country Independence Setter & Getter

## Overview
his project demonstrates the interaction between a smart contract and a user interface (frontend) for a decentralized application (dApp). It allows users to update and retrieve country names and years of independence.

## Description
This project showcases a simple smart contract that stores and updates country information, which can be interacted with through a frontend interface. The contract includes functions to:
* Update country names
* Update years of independence
* Retrieve country details (name and year of independence)

## Getting Started

### Installation
#### Smart Contract 
```
git clone https://github.com/Boluchel/Country-Independence-Setter-Getter.git
cd smart-contract
npm install
npx hardhat compile

```
#### Frontend
```
git clone https://github.com/Boluchel/Country-Independence-Setter-Getter.git
cd frontend
npm install
npm start
```

## Interacting with the Contract
After deployment, you can interact with the contract using the provided frontend interface or a web3 library like Ethers.js just as done in this project.


## Contract Details
* Contract Name: UpdatecountryName
* Functions:
    * updateCountryName(string memory _countryName): Updates the country name.
    * updateYearOfIndependence(uint _yearOfIndepndence): Updates the year of independence.
    * getCountryDetails(): Retrieves the country name and year of independence.

## Frontend Interface
The frontend interface allows users to interact with the smart contract, updating and retrieving country information.

## Authors
Banwo Boluwatife

## License

This project is licensed under the MIT License
