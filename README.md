# Solana-Wallet-Interaction-Project


This project is a simple web application that allows you to connect to a Solana wallet (e.g., Phantom Wallet) and send SOL tokens to a specified account address. It uses the Solana Web3.js library for blockchain interaction.

## Project Overview

![Solana Logo](https://cryptologos.cc/logos/solana-sol-logo.png?v=024)

- Connect Wallet: Click the "Connect" button to connect to your Solana wallet. This project uses the [Phantom Wallet](https://phantom.app/) by default.

- Send SOL: Enter the amount of SOL you want to send in the input field and click the "Send" button to initiate the transaction.

## Getting Started

1. Clone this repository to your local machine.

   ```bash
   git clone https://github.com/ursprash/Solana-Wallet-Interaction-Project.git
   ```

2. Open the `index.html` file in a web browser.

## Usage

### Connect Wallet

1. Click the "Connect" button to connect to your Solana wallet (e.g., Phantom Wallet).

2. If you're using Phantom Wallet, it will prompt you to authorize the connection. Follow the on-screen instructions.

3. Once connected, the "Connect" button will change to "Connected."

### Send SOL

1. Enter the amount of SOL you want to send in the input field labeled "Sol to send."

2. Click the "Send" button to initiate the transaction.

3. You will see a status message indicating the transaction's progress.

4. The transaction will be confirmed on the Solana blockchain.

### Address Ellipsis

The project includes a function that shortens long Solana addresses for display. Addresses longer than 35 characters are displayed as a shortened version with an ellipsis in the middle.

### Troubleshooting

- If you encounter any issues with the connection or transaction, please check the browser's console for error messages.

## Dependencies

- [Solana Web3.js](https://github.com/solana-labs/solana-web3.js): The Solana Web3.js library is used for interacting with the Solana blockchain.

## Notes

- This is a simplified example for educational purposes and may not cover all security and error-handling considerations for a production application.

- The project assumes you have a Solana wallet extension (e.g., Phantom Wallet) installed in your browser.

- Make sure to use a Solana development network (e.g., Devnet) for testing, as sending real SOL tokens on the mainnet can result in financial loss.

## Command
**Note:before all this command solana installed

1.This command is used to generate a new Solana key pair (consisting of a public key and a secret key) and save it to a JSON file.
 ```bash
solana-keygen new -o /home/ursprash/.config/solana/id.json
```
2.This command is used to set the Solana cluster URL to the Devnet cluster.
 ```bash
solana config set --url https://api.devnet.solana.com
```
3.This command is used to request an airdrop of 1 SOL (Solana's native token) to a specified public key on the Solana blockchain.
 ```bash
solana airdrop 1 <Public Key>
```
4.This command is used to check the SOL token balance associated with the currently configured wallet.
 ```bash
solana balance
```

## Contributors

- ursprash

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.


Feel free to customize this README.md file with additional information or instructions specific to your project.
