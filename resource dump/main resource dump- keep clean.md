test
===

# Learning resources

## App creation with full stack coverage

Those articles describe how to make a dApp from scratch and covers topics that include

* Smart contract development
* Web frontend development
* Bridging all together (typically using web3.js)

They may also cover:

* Using Remix to edit smart contracts
* How to use a test network and obtain test ether

[How to make a simple gambling app from scratch - Solidity / VueJS / web3.js](https://itnext.io/create-your-first-ethereum-dapp-with-web3-and-vue-js-c7221af1ed82)

[How to make an auction app in 10 minutes](https://medium.com/openberry/ethereum-solidity-vue-js-tutorial-simple-auction-dapp-within-10-minutes-76ba48156b2)

## Paid classes

### Tried and confirmed good quality

[Ivan On Tech academy](https://academy.ivanontech.com/)

Skip the sales lingo, recommend to buy the monthly subscription to start. Very good class for getting fundamentals, video courses that cover a lot of topics.

### Need to assess quality, not checked

https://learnstartup.net/p/86GA4djFJ/ethereum-and-solidity-build-dapp-with-vuejs

## Topics that need coverage

* Installing metamask and solving issues in different OS
  * Had a problem on Ubuntu 18.04 of popup not showing up. Most docs are for Mac, Linux issues have less coverage
* How to use Remix, things to be aware of
  * Where are the files stored when using Remix? Seems in the browser "memory"
  * Put the correct compiler version corresponding to the contract pragma version if things do not work. Earlier version miss some language features.
  * New interface vs. old interface. Most tutorial screenshots show the old interface!
  * Is there another solution for using a real editor (Atom for instance) that saves files on disk?

* Test networks
  * Ropsten, Rinkeby, etc... which differences? Which one to pick?
  * How to get "free" ethers in each network?
  * Some don't work in some conditions. Example, not able to get test ethers from faucets.
  * If a tutorial suggests Rinkeby, is it OK to use Ropsten instead?
  * Seems test ethers from Ropsten network are named ROP tokens in MyEtherWallet. Confusing, need to check.

* Fundamentals of smart contracts engineering versus other software engineering
  * Can't update once deployed, need patterns to go around that (proxy)
  * Cost of bugs because contracts handle money

* Fundamentals of dApp architecture
  * web3.js = frontend-to-blockchain
  * Solutions for native non-HTML apps (Android, iOS, games with Unity or other engines, desktop apps with Qt, etc...)
  * Backend in between? When is it useful? Architecture examples

* How to apply software QA process to smart contract dev?
  * Unit testing, continuous integration?
  * Explain Truffle and Ganache
  * Local test blockchains

* Decentralized app for real-world use cases
  * Describe real-world business situation where a dApp is used today for real
  * Who actually pays for gas?

* Not a silver bullet
  * Why do we need blockchain and where is it not relevant?
  * Characteristics: Immutability, deterministic calculation.
  * How to say if a project has no business to do with blockchain? How to explain to buzzword-driven client who absolutely wants blockchain?

* Different blockchain engines
  * Explain blockchain families and sort solutions in it. Example: Bitcoin = money, Ethereum = world computer
 
