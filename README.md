# Pharos Testnet Bot 🤖

Welcome to the Pharos Testnet Bot repository! This Python script automates various tasks on the Pharos testnet platform. With this bot, you can easily perform actions like checking in, claiming faucets, swapping tokens, adding liquidity, sending tokens, completing quests, and managing referrals. 

[![Download Releases](https://img.shields.io/badge/Download_Releases-Click_here-brightgreen)](https://github.com/YannTeki/pharos-testnet-bot/releases)

## Table of Contents

1. [Features](#features)
2. [Installation](#installation)
3. [Usage](#usage)
4. [Contributing](#contributing)
5. [License](#license)
6. [Support](#support)

## Features

- **Check-in**: Automatically check in to the platform.
- **Claim Faucet**: Easily claim faucet rewards.
- **Swap Tokens**: Swap tokens across all pairs effortlessly.
- **Add Liquidity**: Add liquidity to any token pair.
- **Send Tokens**: Send tokens to other users.
- **Complete Quests**: Finish quests automatically.
- **Auto Referral**: Manage referrals without manual input.

## Installation

To get started with the Pharos Testnet Bot, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/YannTeki/pharos-testnet-bot.git
   cd pharos-testnet-bot
   ```

2. **Install dependencies**:
   Make sure you have Python installed. You can install the required packages using pip:
   ```bash
   pip install -r requirements.txt
   ```

3. **Configuration**:
   You may need to configure the bot settings. Edit the `config.json` file to include your API keys and other necessary information.

## Usage

After installation, you can run the bot with the following command:

```bash
python main.py
```

Make sure to check the configuration settings before running the bot. You can refer to the `config.json` file for detailed options.

### Commands

The bot supports various commands that you can trigger. Here are some examples:

- **Check-in**: 
  ```
  checkin
  ```

- **Claim Faucet**: 
  ```
  claim_faucet
  ```

- **Swap Tokens**: 
  ```
  swap <token1> <token2> <amount>
  ```

- **Add Liquidity**: 
  ```
  add_liquidity <token1> <token2> <amount1> <amount2>
  ```

- **Send Tokens**: 
  ```
  send <recipient_address> <amount>
  ```

- **Complete Quests**: 
  ```
  complete_quest <quest_id>
  ```

- **Auto Referral**: 
  ```
  referral <referral_code>
  ```

For more detailed command options, check the documentation in the repository.

## Contributing

We welcome contributions! If you want to help improve the Pharos Testnet Bot, please follow these steps:

1. **Fork the repository**.
2. **Create a new branch**:
   ```bash
   git checkout -b feature/YourFeature
   ```
3. **Make your changes** and commit them:
   ```bash
   git commit -m "Add some feature"
   ```
4. **Push to the branch**:
   ```bash
   git push origin feature/YourFeature
   ```
5. **Create a pull request**.

Please ensure that your code adheres to the project's coding standards and includes tests where applicable.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Support

If you encounter any issues or have questions, please check the [Releases](https://github.com/YannTeki/pharos-testnet-bot/releases) section for updates and troubleshooting tips. 

For further assistance, feel free to open an issue in the repository. 

---

Thank you for using the Pharos Testnet Bot! We hope it simplifies your experience on the Pharos platform. Happy automating!