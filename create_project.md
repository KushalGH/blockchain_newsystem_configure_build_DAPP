# Create/Run DAPP
      - For configurations, refer readme.md
      - $ mkdir firstdapp
      - $ cd firstdapp
      - $ truffle unbox webpack
      - make changes in the contract, script, css and migration files
      - [on direct console] $ testrpc  
      - ([at project level] ~/kushalgh/blockchain_newsystem_configure_build_DAPP/FirstDapp) $ truffle compile
      - ([at project level] ~/kushalgh/blockchain_newsystem_configure_build_DAPP/FirstDapp) $ truffle migrate
      - ([at project level] ~/kushalgh/blockchain_newsystem_configure_build_DAPP/FirstDapp) $ npm run dev
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


