# ᝰ.ᐟ Oroswap

Link: [https://testnet.oroswap.org/](https://testnet.oroswap.org/)

## 🚨 Attention Before Running Cli Version

I am not `responsible` for the possibility of an account being `banned`!

## 📎 Node cli version Script features

- Auto swap
- Auto add liquidity
- Support proxy or not
- Mutiple threads, multiple accounts

## ✎ᝰ. RUNNING

- Clone Repository

```bash
git clone https://github.com/Hunga9k50doker/oroswap.git
cd oroswap
```

- Install Dependency

```bash
npm install
```

- Setup config in config.json

```bash
nano config.json
```

- Setup input value

* proxy: http://user:pass@ip:port

```bash
nano proxy.txt
```

### Run with private key | Not private key of evm wallet

- privatekey: how to get => join my channel: https://t.me/airdrophuntersieutoc

```bash
nano privateKeys.txt
```

- Run the script

```bash
node main.js
```

### Run with seed pharse (12 or 24 recover pharse) | Create this on keplr wallet

```bash
nano seed.txt
```

- Run the script

```bash
node seed.js
```
