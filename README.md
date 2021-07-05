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
    * After accessing the editor, you have to left click on the menu button (three lines on the top right corner), then click on manage palette, switch to the install tab and search for the node-red-contrib-neo4j package and install it. This will add the node required by our flows ensuring the dependency.

### Install Nodejs
* Node.js: Before installing Node-Red, a Node.js installation is required. We have installed Node.js version v8.9.3.
   * On Ubuntu machines we have to run the following commands:
      *    sudo apt-get update
      *    sudo apt-get upgrade
      *    sudo apt-get install node.js -y
      *    sudo apt-get install npm -y
   * On Windows machines we can download the appropriate installer from https://nodejs.org/en/download and execute it.

### Install Front End
* Front End: We have developed a web front end, useful for end users of our application. It provides a Graphical User Interface
   * Based on HTML, Javascript, Vue Javascript framework and other libraries
   * Running: it is deployed on our server (and cloud servers as well) and accessible in



### Install Java
* Most of the systems used are built on top of java engines so a Java distribution needs to be installed in the system before anything else.
   * On Ubuntu machines a simple list of commands is enough to install the latest distribution of Java:
      * sudo add-apt-repository ppa:webupd8team/java
      * sudo apt-get update
      * sudo apt-get install -y oracle-java8-installer
      * sudo apt-get update
   * On Windows machines we have to download

### Operating System
We have tested the platform on Windows 10 and Ubuntu 18.04 LTS, Ubuntu 20 but all of the software listed here is available in a large number of other distributions.


### Install Truffle Suite
Truffle suite:
npm install truffle -g
More installation instructions could be found in the following link: https://www.trufflesuite.com/truffle

### Install Solidity
Ethereum, "Solidity," Ethereum, [Online]. Available: http://solidity.readthedocs.io.

### Install Quorum Blockchain Network
https://github.com/synechron-finlabs/quorum-maker
https://github.com/jpmorganchase/quorum-examples/tree/master/examples/7nodes









