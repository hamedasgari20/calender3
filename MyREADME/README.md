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