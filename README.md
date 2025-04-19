# 🤖 Somnia Testnet Automation Bot

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![License](https://img.shields.io/badge/License-MIT-green)
![Status](https://img.shields.io/badge/Status-Active-success)

This repository contains an advanced automation bot for interacting with the Somnia Testnet, enabling seamless token deployments, swaps, and minting operations.

## 🚀 Features

- ✨ Multi-wallet support
- 🔒 Proxy support for enhanced privacy
- 📝 Automated token deployments
- 🎯 Automated minting operations
- 💱 Token swapping functionality
- 🤖 Transaction automation
- 🎮 Interactive menu system

## 📋 Prerequisites

- Python 3.8 or higher
- pip (Python package installer)
- A wallet with some test tokens for gas fees

## 💻 Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/Somnia-Testnet-Automation.git
cd Somnia-Testnet-Automation
```

2. Install required dependencies:
```bash
pip install -r requirements.txt
```

## ⚙️ Configuration

1. Set up your configuration files:
   - Edit `config.json` with your network settings
   - Add your private keys to `pvkey.txt` (one per line)
   - (Optional) Add proxy configurations to `proxies.txt`

2. Prepare wallet addresses:
   - Add wallet addresses to `address.txt`
   - Configure ERC20 addresses in `addressERC20.txt`
   - Set up faucet addresses in `addressFaucet.txt`

## 📜 Available Scripts

The bot includes several automation scripts in the `scripts/` directory:

| Script | Description |
|--------|-------------|
| `buymeme.py` | Purchase MEME tokens |
| `sellmeme.py` | Sell MEME tokens |
| `deploytoken.py` | Deploy new ERC20 tokens |
| `faucetstt.py` | Interact with testnet faucets |
| `mintping.py` | Mint PING tokens |
| `mintpong.py` | Mint PONG tokens |
| `mintsusdt.py` | Mint test USDT |
| `sendtoken.py` | Send tokens between addresses |
| `sendtx.py` | Send basic transactions |
| `swapping.py` | Perform token swaps |
| `swappong.py` | Swap PONG tokens |

## 🎯 Usage

1. Start the main bot:
```bash
python main.py
```

2. Follow the interactive menu for available options

3. For individual scripts:
```bash
python scripts/scriptname.py
```

## 🛡️ Safety Tips

- ✅ Always test with small amounts first
- 🔐 Keep your private keys secure and never share them
- 👀 Verify all addresses before transactions
- 🧪 Use test networks for initial testing

## ❗ Troubleshooting

If you encounter issues:
1. 🌐 Check your network connection
2. 💰 Verify your wallet has enough gas fees
3. 📝 Ensure all configuration files are properly set up
4. 📋 Check the logs for detailed error messages

## 🤝 Contributing

Feel free to:
- Submit issues
- Create pull requests
- Suggest new features
- Help with documentation

## ⚠️ Disclaimer

This bot is for educational and testing purposes only. Use at your own risk. Always verify transactions before confirming them.

---
Made with ❤️ By TRACKKO
