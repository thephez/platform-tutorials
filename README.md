# readme-tutorials

## Install

1. `git clone https://github.com/thephez/readme-tutorials.git`
1. `npm install`

## Usage

1. Check connection: `node connect.js`
1. Create wallet: `node create-wallet.js`
1. Add funds to the address reported in the previous step via https://testnet-faucet.dash.org/
1. Create an `.env` file that sets `MNEMONIC` to the wallet mnemonic from step 2. See [`.env.example`](./.env.example) for an example `.env` file.
