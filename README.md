📞 Contact

> [Termux guides if you run on mobile](https://github.com/MeoMunDep/Guides-for-using-my-script-on-termux)


> If you encounter any issues or have questions, feel free to reach out:

- Contact: [Link](t.me/MeoMunDep)
- Group: [Link](t.me/KeoAirDropFreeNe)
- Channel: [Link](t.me/KeoAirDropFreeNee)

> Help me with your referral [MeshChain Extension](https://t.me/KeoAirDropFreeNe/257/16137) - [MeshChain Telegram](https://t.me/meshchain_bot?start=T_6713068747)

## 🚀 Getting Started

To get started with the bot, follow these steps:

0. **Dowload NodeJS to run the bot**

Before running the bot, make sure you have the following installed:

- **Node.js** (Version: `22.11.0`)
- **npm** (Version: `10.9.0`)

Download Node.js and npm here: [Download Link](https://t.me/KeoAirDropFreeNe/257/1462).

-> Double click on `setup.bat` for windows or `setup.sh` for linux/mac if you want to run automatically, remember to fill all the necessary data.

1. **Install Dependencies and Modules:**

   ```
   npm i user-agents axios colors p-limit https-proxy-agent socks-proxy-agent crypto ws uuid
   ```

2. **Prepare Configuration Files:**

   > You'll need to set up a few configuration files for the bot to work properly.

## 📁 Configuration Files

### 1. `configs.json` 📜 - Adjust configuration

```json
{
  "timeZone": "en-US",
  "delayEachAccount": [5, 8],
  "timeToRestartAllAccounts": 300,
  "numberOfAccountsRunInOneTime": 100,
  "isDoTasks": true,
  "isPlayingGames": true,
  "referralCode": "6713068747" - Your referral code, dont change it if you want to help me ^^
}
```

### 2. `extension_datas.txt` 🗂️ - Get it from here >>> [Extension version](https://t.me/KeoAirDropFreeNee/1511)

```txt -
ey...
ey...
ey...
```

### 2.1. `telegram_datas.txt` 🗂️ - Get it from here >>> [Telegram version](https://t.me/KeoAirDropFreeNe/257/6879)

```txt -
query_id.../user...
query_id.../user...
query_id.../user...
```

### 3. `wallets.txt` 💼 - Cannot update yet.

- Wallets generator: [Link](https://github.com/MeoMunDep/Automatic-Ultimate-Create-Wallets-for-Airdrop)

```txt - wallet address
abc...xyz
abc...xyz
abc...xyz
```

### 4. `proxies.txt` 🌐 - Proxy is an option. If you have one, fill it in; otherwise, leave it blank.

```txt
http://user:password@host:port
https://user:password@host:port
socks4://user:password@host:port
socks5://user:password@host:port
```

💡 Usage:

> You need to `cd` to the file after extract it.
> To run the bot, use the following command: 

- For **telegram** version:

```bash
cd meshchain; node telegram_meomundep
```
 
- For **extension** version:
 ```bash
 cd meshchain; node extension_meomundep
``` 
> If you want to run both bot, use this command:
```bash
cd meshchain; node index_meomundep.js
````

🎇Enjoy!
