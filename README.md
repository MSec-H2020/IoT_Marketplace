# IoT_Marketplace

## Overview of the IoT Marketplace
IoT marketplace users can exchange IoT sensor data and media easily, securely and with complete anonymity. 
It allows the real-time matching of supply and demand enabling the creation of liquid markets with profitable business models of the IoT stakeholders.
IoT devices and humans using mobile applications and APIs are able to exchange data and value through the M-Sec blockchain-based implementations.



## Required Tools and dependencies
The following tools and dependencies are required to install and use the IoT Marketplace:
1. NodeRed
2. Nodejs
3. MySQL
4. Ethereum/Quorum Blockchain
5. Nodejs and Javascript

### Install NodeRed
* Node-Red: Node-RED is a powerful visual tool for wiring together hardware devices, APIs and web-services, create flows and connect distributed components into a common IoT application [https://nodered.org/].
* Installing Node-Red: The easiest way to install Node-RED is to use the node package manager, npm, which comes with Node.js [https://nodered.org/docs/getting-started/installation]. Installing as a global module adds the command “node-red” to your system path:
    * For Ubuntu:
         * sudo npm install -g --unsafe-perm node-red
    * For Windows, execute CMD with administrator rights and then execute:
         * npm install -g --unsafe-perm node-red
    * Version: We have installed Node-Red v0.17.5
    * Running: after installing Node-Red as a global npm package, open a terminal and run the “node-red” command. You can then access the Node-RED editor by pointing your browser at: http://localhost:1880
    * After accessing the editor, you have to left click on the menu button (three lines on the top right corner), then click on manage palette, switch to the install tab and search for the node-red-contrib-neo4j package and
