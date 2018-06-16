# Simple Voting Dapp for web3.js v1.0

### Credits :
- Simple voting dapp based on [Mahesh Murthy's Medium article](https://medium.com/@mvmurthy/full-stack-hello-world-voting-ethereum-dapp-tutorial-part-1-40d2d0d807c2)
- [Video tutorial by Siraj Raval](https://www.youtube.com/watch?v=gSQXq2_j-mw)

### NOTE :
If you are following the [Video tutorial by Siraj Raval](https://www.youtube.com/watch?v=gSQXq2_j-mw) to create the wrapper around the application showed in the blog, make sure you install testrpc using - 

```
npm install ethereumjs-testrpc web3@0.20.1
```
As the API for the web3.js v1.0 changed. See [here](https://web3js.readthedocs.io/en/1.0/) for the changes.

### Installation

Clone repository and run
```
npm install
```
Then launch the testpc server with
```
npm run ganache
```
and from a separate shell
```
npm run http_server
```

Then point your browser to `http://localhost:8000` for the web version of the voting app.
