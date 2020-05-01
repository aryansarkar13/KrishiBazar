# TechKrishi
  A DECENTRALIZED AGRO-MARKET WHERE THE FARMERS CAN EASILY RAISE FUND FOR CULTIVATION ALONG WITH THE CUSTOMERS IN HIS HAND FOR BUYING HIS PRODUCE.

# Setup
 Setup up Ganache and Metamask on your System (Windows)
 
 https://steemit.com/ganache/@matbest/setting-up-ganache-and-metamask-on-my-windows-10-home-laptop

 # Run the Dapp
Step 1. Start ganache.

Step 2. Go to KrishiTech Directory and do 'npm install'

Step 3: truffle migrate

Step 4: Important:

In  src directory --> app.js

Line number 43820 --->

change the variable conaddress = "0x363F44A99e7DCcB7e40D41812298dA9a92EEE3fd"; 

The above value of contract address should be changed to the result you get when you do truffle migrate.

When you do truffle migrate you get a contract address !!!
Put that value to conaddress!!!


Step 5: 'npm run dev' to start lite-server

Step 6: Goto localhost:3000
