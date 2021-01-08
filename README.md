# Cryptocurrency-price-CLI
It is a command line index based application developed using node.js to show the price of cryptocurrency on command line
Command line interface written in Node.js to check cryptocurrency prices

Register an API key at https://nomics.com and you will get your api key at your mailbox

Api 

Usage
```
npm install

npm link

```
Commands
# Help & Commands

```coindex -h```

# Version
```coindex -V```

# API Key Commands
```
coindex key set
coindex key show
coindex key remove
```

# Crypto Check Commands
```
coindex check price
```

# Check Specific Coins (default: BTN,ETH,XRP)
```
coindex check --coin=BTC,ETH
```

# Choose Currency (Default: USD)
```
coindex check --cur=EUR
```
Version
1.0.0

License
MIT
