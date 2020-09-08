# Instructions

## RUNNING AND TESTING THE APPLICATION – BALLOT DAPP
- Click on Ganache, and when the Ganache UI opens, click Quickstart.
- Connect it with MetaMask using the seed phrase.
- Ganache and Metamask should show the same accounts and Ether values.
Reset the accounts 1,2 and 3 in MetaMask.
```sh
$ cd ballot-contract
$ truffle compile
$ truffle migrate –reset
$ cd ..
$ cd ballot-app
$ npm install
$ npm start
```
You should be able to see the app in `localhost:3000`

- Restore the accounts in the Metamask to connect to the Ganache test chain.

Now, you are ready to test the application.