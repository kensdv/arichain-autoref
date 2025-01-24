# Ari Chain Wallet Auto Referral Bot

This bot automates the process of creating accounts and using referral codes for the AriChain Wallet.

## Features

- Automatically generates random email addresses.
- Uses proxies to avoid IP bans.
- Logs the created accounts.
- Handles email verification.

## Requirements

- Node.js v18.20.5 LTS or latest.
- npm (Node Package Manager)
- Use 2Captcha Services [2Captcha](https://2captcha.com/), [AntiCaptcha](https://anti-captcha.com/), free version you can using gemini apikey.
- email and password gmail (for password not your email password, use app password)
- completely how to use it [here](https://youtu.be/_rAoQeKpEtM?si=SLicWKn-AurwE8oa).

## Installation

1. Clone the repository:

   ```sh
   git clone https://github.com/ahlulmukh/arichain-autoreff.git
   cd arichain-autoreff
   ```

2. Install the dependencies:

   ```sh
   npm install
   ```

3. Create a `proxy.txt` file in the root directory and add your proxies (one per line).

4. change `config.json.example` to `config.json`

5. change your email, password (for get password you can see this video [Here](https://youtu.be/_rAoQeKpEtM?si=SLicWKn-AurwE8oa)), gemini apikey [Here](https://aistudio.google.com/app/apikey),

6. If you want using 2 Captcha service you can fill your apikey in `config.json` and change `"captha2Apikey": "your_2captcha_apikey",` with your apikey.

## Usage

1. Run the bot:

   ```sh
   node .
   ```

2. Follow the prompts to enter your referral code, address to transfer token and the number of accounts you want to create, and dont forget too choice your solve captcha too.

## Output

- The created accounts will be saved in `accounts.txt`.

## Notes

- Make sure to use valid proxies to avoid IP bans.
- The bot will attempt to verify the email up to 5 times before giving up.

## Stay Connected

- Channel Telegram : [Telegram](https://t.me/elpuqus)
- Channel WhatsApp : [Whatsapp](https://whatsapp.com/channel/0029VavBRhGBqbrEF9vxal1R)

## Donation

If you would like to support the development of this project, you can make a donation using the following addresses:

- Solana: `FPDcn6KfFrZm3nNwvrwJqq5jzRwqfKbGZ3TxmJNsWrh9`
- EVM: `0xae1920bb53f16df1b8a15fc3544064cc71addd92`
- BTC: `bc1pnzm240jfj3ac9yk579hxcldjjwzcuhcpvd3y3jdph3ats25lrmcsln99qf`

## Disclaimer

This tool is for educational purposes only. Use it at your own risk.
