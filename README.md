


**GethDesk (The original version this is the Ether-1 Version)** — is an open source application to simplify work with “Ethereum Geth Go” console client and to show you data about your node current condition without using console commands.
#### Install this app as [chrome extension](https://chrome.google.com/webstore/detail/ethereum-gethdesk/ldbikceofpgkjbmoijglmnaphdcfmklp?hl=uk) or go directly to <a href='http://cryptobit-env.7hiybanifg.eu-central-1.elasticbeanstalk.com/gethdesk/index.html'>GethDesk</a> url.
<a href='https://chrome.google.com/webstore/detail/ethereum-gethdesk/ldbikceofpgkjbmoijglmnaphdcfmklp?hl=ru'  target="_blank">
 <img src='https://github.com/edmlbox/CryptoBit-Bitcoin-wallet/blob/master/readmeIMG/chrome-web-store.png'/>
</a>

## Core functionalities
### Dashboard
* Blockchain current synchronization progress.
* Enabled and Disabled **"APIS"**.
* To which network your node connected. (**Main** or **Testnet** and name of
   the network.);
* **"Open"** or **"Not"** your node to network connections.
* Number of peers connected to your node. (Default maximum is 25, if not
   specified else.);
* Current Ethereum protocol version.
* Node mining status **"Yes"** or **"Not"**, if yes than you get the hashrate speed.
* Current price per gas in ether. (Other units available also).
* Mining default reward address. (You can change it).



## Accounts Manager
* Number of accounts your node owns.
* Accounts addresses with current balance in ETHO.
* Create new password protected accounts.
* Import private keys and encrypt them with password.


## You can send a payment request to any email address or print it as pdf.

## Mining
* Start CPU mining with the required number of cores.

#### Keep in mind. Important!

1. On the Ether-1 Mainnet network mining won't start until your blockchain is fully synchronized! Mining will be scheduled to start automatically when blockchain fully synchronized.

* Mining hashrate speed.
* Visualized mining chart.
* Choose a default mining reward address.

## Node Info
* Your running node all information **[Default Database Directory**, **Node name**, **Node
  Id**, **Node Ip**, **Listen Addr**, **Enode**.]

* Detailed information about each peer connected to your node including: [**Node name**, **Enode**, **Id**,
  **LocalAddress**, **RemoteAddress**, **Caps**, **Network Static**, **Network Trusted**,
  **Inbound**, **Difficulty**, **Head**, **Version**.]

## How to use Node Monitor:

#### `geth --rpc --rpcaddr 0.0.0.0 --rpccorsdomain '*' -rpcapi="admin,personal,net,web3,miner,eth,txpool,debug"`

