# Ambo
Borrow and Lend Crypto on Ambo

Don't let your assets sit idle! Ambo allows you to earn money from holding crypto, and borrow funds whenever you need.

# About
This repository is home to the Ambo web application--a dApp that allows users to borrow and lend their crypto assets with the Compound Finance MoneyMarket.

### TOC:
[Usage](#usage)

[Goals](#goals)

[Primary Tools & Technologies](#primary%20tools%20%26%20technologies)

[Folder Structure](#folder%20structure)

[Contact Info](#contact%20info)

# Usage

### Branches
The default branch is __dev__.
Changes are merged in from __dev__ to __master__ before being deployed to production.

### Requirements

- Node >= 6
- npm >= 5.2
- Mongo

1. Clone this repository
1. Edit config files
1. Run the api server
```
$ cd ambo
$ cd api
$ yarn install
$ npm run dev
```
4. Run the client
```
$ cd ambo
$ cd client
$ yarn install
$ npm run start
```


# Goals

The major goals of this project were
1. Make the experience of lending and borrowing crypto as seamless and as easy as possible.
1. Create a secure application using the Compound Finance protocol.
1. Do it quickly! (Within 5 days)

# Primary Tools & Technologies

### Client:
- [React.js v16.8.5](https://reactjs.org/)
- React Router
- [Reactstrap](https://reactstrap.github.io/)
- Redux
- Redux Persist

### API:
- [Node.js](https://nodejs.org/)
- [Express](https://expressjs.com/)

### Integrations:
- [Compound Finance](https://compound.finance/)
- [web3.js](https://github.com/ethereum/web3.js/)

### Database:
- Mongo

# Folder Structure

```
|
├── api - API server using web3 to interact with Compound Finance, and other Ethereum related APIs
└── client - Frontend web interface
```

# Contact Info

For questions please contact lead maintainer @thevaleriemack
