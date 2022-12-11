# scaffold eth sample

Example project use alongside the getting started exercises recommended
in [Scaffold-ETH](https://github.com/scaffold-eth/scaffold-eth#-scaffold-eth)

* [Solidity By Example](https://solidity-by-example.org/)
* [nvm commands](https://gist.github.com/chranderson/b0a02781c232f170db634b40c97ff455)


Notes

* Use node 16 - node 18 will not run the front end
* Solidity version is 0.8.4

## Working with the Examples

* Edit YourContract.sol in packages/hardhat/contracts
* Main directory - yarn deploy
* Interact in the browser


### Adding a New Contract

* See [this section](https://docs.scaffoldeth.io/scaffold-eth/toolkit/how-tos-and-troubleshooting/adding-a-new-contract)
* For example
    * packages/hardhat/contracts/HellowWorld.sol
    * add it to packages/hardhat/deploy/00_deploy_your_contract.js.
    * add a new contract section to packages/react-app/src/App.jx

### Notes - Solidity By Example

* [Hello world](https://solidity-by-example.org/hello-world/)