# CoinApp CLI

 Command line interface written in Node.js to check cryptocurrency prices

 Register an API key at https://nomics.com

# Usage

    npm install
    npm link

# Commands

. Help & Commands

    coinapp -h

. Version

    coinapp -V or coinapp --version

. API Key Commands

    coindex key set
    coindex key show
    coindex key remove

. Crypto Check Commands

    coindex check price

. Check Specific Coins (default: BTN,ETH,XRP)

    coinapp check --coin=BTC,ETH

. Choose Currency (Default: USD)

    coinapp check --cur=EUR

# Version

    1.0.0

# License

    MIT
