### btc_marketcap

##### Setting up
```
download truffle ganache (test blockchain replaces test-rpc)
npm install -g truffle 
npm install 
// NOTE:as of July 20 2018 web3 1.0.0* fails to install?! 
// instead uses web3 ^0.20.6 - if necessary install 0.20.* by the following:
// npm install web@^0.20.0  
// there is a package-web3-1.0.0beta24.json for later use of web3 ^1.0.0
// NOTE: web3 ^1.0.0 supports websocket provider
start ganache
truffle compile
truffle migrate
```

##### Running marketcap oracle
```
node oracle.js
```

##### Running client - initially run twice to get first update 
```
node client.js
```
