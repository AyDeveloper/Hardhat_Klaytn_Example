# Harhat_Klaytn_Example

This is a simple example for setting up a hardhat project for Klaytn putting in to consideration its fixed gas price model.

Klaytn makes use of a fixed gas price model. This means developers would need to be extra careful when using Ethereum native tooling for they have to set the right amount of gas when creating a transaction. The need to put this into consideration when you are using Ethereum tools on Klaytn is the reason behind this repo. 

This would guide you into how to set up a project, test and deploy it to klaytn putting into consideration the Klaytn compatible gas price using Hardhat and ethers js.

## Installation
1. Clone this repo:

```shell
git clone https://github.com/Timidan/diamond-3-hardhat.git
```

2. Install NPM packages:

```shell
cd diamond-3-hardhat
npm install or yarn install
```

3. Compile Contract

```shell
  npx hardhat compile
```

4. Start Hardhat Node

```shell
  npx hardhat node
```

5. Deployment

```shell
npx hardhat run scripts/deploy.ts --network localhost
```

5. Run tests

```shell
npx hardhat test test/index.ts --network localhost
```


# Other Links
Using Ethereum tools in Klaytn https://medium.com/klaytn/using-ethereum-tools-in-klaytn-dc068d48de04
