- Download truffle CLI
```bash
npm i -g truffle
```
- Download Ganache

- Download MetaMask extension -> create password

- Open Ganache -> create workspace with server http://127.0.0.1:8545 and networkID 1337
- Open MetaMask -> create network with url http://127.0.0.1:8545 and chain id 1337, currency ETH -> click create -> select custom network
- Open metamask -> import account from Ganache workspace by private Key

```bash
truffle migrate --reset

cd client
npm start

cd backend
npm start
```
- Confirm MetaMask connect client

- Create nft
- Sell/Buy