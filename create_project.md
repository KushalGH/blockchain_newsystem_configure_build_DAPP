# Create/Run DAPP
      - For configurations, refer readme.md
      - $ mkdir firstdapp
      - $ cd firstdapp
      - $ truffle unbox webpack
      - make changes in the contract, script, css and migration files
      - ([at global level]) $ testrpc  
      - ([at project level]) $ truffle compile
      - ([at project level]) $ truffle migrate
      - ([at project level]) $ npm run dev
      - Import testrpc account to MetaMask. You will get some initial Ethers
       
# Deploy on Live Ethereum Network

      - To Setup Ethereum Network, follow any one of these:

## Installing geth follow 

      - You can install geth on your system and sync to the live network.
      - $ sudo add-apt-repository -y ppa:ethereum/ethereum [at global level]
            reference: https://github.com/ethereum/go-ethereum/wiki/Installing-Geth#install-on-ubuntu-via-ppas
      - $ sudo add-apt-repository -y ppa:ethereum/ethereum
      - sudo apt-get update
      - sudo apt-get install ethereum

## Installing geth Parity

      - https://github.com/paritytech/parity-ethereum
      - $ curl https://sh.rustup.rs -sSf | sh
      - $ sudo snap install parity
      
## Install Infura

      - It will provide an end point by which you can directly connect to the network.
      - Signup to InFURA [https://infura.io/dashboard]


# Commands to run on Ethereum Live Network
      -  $ testrpc  
      -  $ truffle compile
      -  $ truffle migrate -- 
      - ([at project level] ~/kushalgh/blockchain_newsystem_configure_build_DAPP/FirstDapp) $ npm run dev
      - Import testrpc account to MetaMask. You will get some initial Ethers

# Trying to build using Ropsten  
      


      - [at project level & globally] npm install --save ethereumjs-wallet
      - [at project level & globally] npm install web3-provider-engine@14.0.6
      - [at project level & globally] npm install truffle-hdwallet-provider
      - [at globally level] sudo npm install -g web3 --unsafe-perm=true --allow-root
      sudo apt-get install build-essential


      - Updated truffle.js with new code
      - Connect MetaMask with ropsten Network, and add some ether using facet
      - [at project level & globally] npm install dotenv
            - https://www.npmjs.com/package/dotenv
      - Add new file .env in your project root directory.
            - The key which you have to put in the .env can be obtained from MetaMask. It is your private key, don't share with anyone.

      - [at project level & globally] $ npm install truffle-wallet-provider

      - truffle comile [It should work, if everything is fine]
      - truffle migrate --network ropsten.


HAPPY CODING!! Your contract should be deployed on Ropsten network.
      - https://ropsten.etherscan.io/address/<your deployed contract address>   
      https://ropsten.etherscan.io/address/0x33b00bf847a5c9fbba1ab2d68cb55c39d8e01a29   
      
