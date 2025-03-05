# Stellar Wallet Generator
![Example of Stellar Wallet Generator](https://stellarfox.net/logo.542886ac.svg)

## Description

**Stellar Wallet Generator** is a web application that generates wallets for the **Stellar** network using JavaScript and HTML. The project allows users to securely create public and private keys and provides an easy way to generate addresses for use on the Stellar network.

This project was developed to help users quickly generate Stellar wallets without the need to install any additional software. The wallet generator uses cryptographic libraries to create keys and addresses, ensuring a high level of security.

## Key Features

- **Generate public** and **private** keys.
- Generate a **Stellar address** based on the public key.
- Visualize wallet details (public key, private key, and address).
- Easy to use: generate wallets directly in your browser.

## How to Use

1. Go to the wallet generator page.
2. Click the "Generate Wallet" button.
3. Retrieve the **private key**, and **Stellar address**.
4. Copy the necessary details for use in your Stellar network.

## Example Usage

### Step 1: Generate Wallet

After clicking the "Generate Wallet" button, the generated public and private keys as well as the Stellar address will be shown.

### Step 2: Example Output

Here’s an example of what the result might look like:

- **Private Key**: SA7XVRPLJKDVGZB2D6ZAYKJLRQNDQK4D9KNX4T44ZED5R2V8FV6Q
- **Stellar Address**: GCUYQH6YH4F3A7JQPKTKPS3AW5FJ9XW2V4CTY6QF7A3JZ7E9P7F3Y5E

## Technologies

- **HTML5** — for structuring the web page.
- **JavaScript** — for key generation and user interaction.
- **Stellar SDK** — for interacting with the Stellar network.

## Installation and Running Locally

To run the generator locally, download the repository and open the `index.html` file in your browser.

```bash
git clone https://github.com/Stellar-SDK/stellar-wallet-generator.git
cd stellar-wallet-generator
open index.html
