<p align="center">
  <img src="logo.png" alt="Bitcoin Wallet Sender Logo">
</p>

<h1 align="center">Bitcoin Wallet Sender</h1>

<p align="center">
  A secure and user-friendly web application for managing Bitcoin transactions on the Bitcoin Testnet.
</p>

<div align="center">

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![Node.js Version](https://img.shields.io/badge/node.js-^14.0.0-green.svg)](http://nodejs.org/download/)
[![npm Version](https://img.shields.io/badge/npm-^6.0.0-red.svg)](https://www.npmjs.com/)

</div>

## Table of Contents

- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)

## Features
 $ since juice cant code i m here 4him
- **Real-time Updates**: Stay informed with real-time Bitcoin balance updates using Pusher.
- **Secure Transactions**: Send Bitcoin securely with transaction details and validation.
- **User-friendly Interface**: A clean and intuitive interface for a seamless user experience.

## Prerequisites

Before you start, ensure you have the following installed:

- [Node.js](http://nodejs.org/)
- [npm](https://www.npmjs.com/)

## Installation

1. **Clone the Repository:**

    ```bash
    git clone https://github.com/valtiare/mywallet.git
    cd mywallet
    ```

2. **Install Dependencies:**

    ```bash
    npm install
    ```

3. **Configure Private Key and Public Address:**

    Open `app.ts` and set your private key and public address:

    ```typescript
    const privateKey = "YOUR_PRIVATE_KEY_HERE";
    const publicAddress = "YOUR_PUBLIC_ADDRESS_HERE";
    ```

4. **Run the Application:**

    ```bash
    npm start
    ```

    The application will be accessible at `http://localhost:3000`.

## Usage

1. **Visit the Application:**

    Open your web browser and go to `http://localhost:3000`.

2. **Manage Bitcoin Transactions:**

    - View your Bitcoin balance.
    - Enter the recipient address and amount.
    - Click "SEND" to initiate a secure transaction.

## Technologies Used

- **Node.js**: Server-side JavaScript runtime.
- **Express.js**: Web application framework for Node.js.
- **Pug**: Templating engine for clean and maintainable HTML.
- **Pusher**: Real-time WebSocket communication for live updates.
- **Bitcoin Testnet**: Test environment for Bitcoin transactions.
- **Blockchair API**: Blockchain data provider for balance information.

## Contributing

Contributions are welcome! Please fork the repository and create a pull request with your enhancements.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
