# KStratum 🏊
### Stratum adapter for Kaspa!

## Features
* Light, uses about 20 MB ram(nearly no CPU usage!) on a typical computer.
* Supports multiple miners per instance.
* Zero fee solo Stratum mining(Time to ditch pools?).
* Supports multiple networks(Testnet, mainnet...).

## Usage
Install NodeJS 16 from [here](https://nodejs.org/) and run KStratum by ``npx kstratum@latest <arguments>`` on command line.

### Arguments
* ``--node <ip/domain:port>``: Switchs to another node. Default: `79.120.76.62:16110`
* ``--address <address>``: Sets mining address.
* ``--port <port>``: Sets Stratum listening port. Default: `16112`
* ``--listen-address <ip/domain>``: Sets Stratum listening address. Default: `127.0.0.1` (**Note** to expose the KStratum service to your local network, use `0.0.0.0`)

#### Sponsored by [lolMiner](https://github.com/Lolliedieb/lolMiner-releases)
