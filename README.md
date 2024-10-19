Hi, We are Bounty Hunter Bit Busters 😁

So, basically we are trying to build an decentralized web app which serves as a platform between employees to chat among themselves with or without revealing their actual names.
We are trying to add more features such as voice calls, voice note, etc. but due to lack of time, we could'nt do this in these 3 days.

How to Run this app?

* First of all, you need to have a MetaMask account and you should have connected it to fuji testnet and add funds using Fuji TestNet faucet.
* First go to "https://remix.ethereum.org/" and create a file named Database.sol and copy the code which is already included in the root directory of our project.
* Then, click on "Solidity compiler" in the remix IDE and click on "Compile Database.sol".
* Then, click on "Deploy and run transactions" and select environment as "Integrated Provider - MetaMask" then proceed with connection to MetaMask wallet.
* Now copy the abi which is generated and paste it in the abi.js file.
* Then, from terminal of remix IDE, click on the line which has green tick beside it and copy contract address and replace your contract address with the one which is already present in the App.jsx file inside src/components.
* Then, run "npm start" from the root directory of the folder.
* Go to "localhost:3000".

* To connect with a friend, even they should have a MetaMask wallet connected with Fuji testnet with test funds provided by faucet.
* Then, click on new chat and fill the wallet address of your friend in the Public key placeholder and enter any name you want and enjoy chatting.
