# Simple web3 calendar that charges Ether to schedule a meeting

### Step 1: Install prerequisites
Install __Node.js__ and __npm__ and make directory __calend3__
### Step 2: initialize the project
Then inside of the calend3 directory, initialize the project ```npm init -y```
### Step 3: Install hardhat
__Hardhat__ is an Ethereum development environment that allows us to test, compile, and run our smart contract code. ```npm install --save-dev hardhat```
### Step 4: Create sample hardhat project
type ```npx hardhat``` and select __create a basic sample project__ then run ```npx hardhat``` to see __hardhat CLI command__

some of the commands listed below:
1. npx hardhat accounts
2. npx hardhat test
3. npx hardhat compile

### Step 5: Change some defaults
1. Delete the sample contract ```contracts/Greeter.sol```. We will start from scratch.
2. Rename ```scripts/sample-script.js``` to ```deploy.js```
3. Rename ```test/sample-test.js``` to ```test.js```
### Step 6: Create smart contract
Add ```Calend3.sol``` in the __contracts/__ directory and compile ```npx hardhat compile```
### Step 7: Test SmartContract
write test for SmartContract in __test/test.js__ and compile ```npx hardhat test```
### Step 8: Setting up an ethereum wallet (metamask)
Prepare __MetaMask__ and connect to __Goerli__ testnet and Charge your wallet [Read More ...](https://hackingthemarkets.com/posts/calend3-metamask/)
### Step 9: Deploy Smartontract
__Alchemy__, a blockchain developer platform that provides node infrastructure for us. [Sign up](https://www.alchemy.com/)
### Step 10: Connect app to testnet 
Follow this guide [Reab more](https://hackingthemarkets.com/posts/calend3-alchemy/)
### Step 11: Create a deploy script
Edit __scripts/deploy.js__ 
1. deploy SmartContract __localy__ ```npx hardhat run scripts/deploy.js```
2. deploy SmartContract to __testnet__ ```npx hardhat run scripts/deploy.js --network goerli```
### Step 12: Check status
We can see our transaction on the [Goerli Testnet Etherscan](https://goerli.etherscan.io/)


