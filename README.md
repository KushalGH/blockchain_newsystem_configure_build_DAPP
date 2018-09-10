# blockchain_newsystem_configure_build_DAPP
This is a getting started Repository for setting up new System for BlockChain on Ubuntu System.

- I have formatted my system and installed Ubuntu. Before, I was coding on Blockchain on Windows operating system. The reason I moved to Ubuntu is because, I was getting issues with Geth and few other things on windows OS.

# Development Environment Setup on Ubuntu for BlockChain

1. nodeJS and npm version install 
      - $ sudo apt install curl
      - $ curl -sL https://deb.nodesource.com/setup_6.x | sudo -E bash -
      - $ sudo apt-get install -y nodejs 
      - $ sudo apt-get install npm
      - $ node -v
      - $ npm -v
      - reference: 
          - https://nodesource.com/blog/installing-node-js-tutorial-ubuntu/
          - https://www.digitalocean.com/community/tutorials/how-to-install-node-js-on-ubuntu-16-04
          
 
2. Install Git
      - $ sudo apt install git
      - $ git config --global user.name "KushalGH"
      - $ git config --global user.email "kushalseth1408@gmail.com"
      - $ cat ~/.gitconfig
      - $ git --version
      - reference: 
          - https://help.ubuntu.com/lts/serverguide/git.html.en
          - https://www.liquidweb.com/kb/install-git-ubuntu-16-04-lts/
          
3. Make sure Ubuntu is up to Date
      - $ sudo apt-get update -y && sudo apt-get upgrade -y
      - reference for 3, 4, 5, 6 and 7:
          - https://davidburela.wordpress.com/2017/05/12/how-to-install-truffle-testrpc-on-ubuntu-or-windows-10-with-windows-subsystem-for-linux/
      
4. Install build essentials & python. lots of NPM libraries require these- 
      - $ sudo apt install build-essential python -y

5. Installing nvm
      - $ curl -o- https://raw.githubusercontent.com/creationix/nvm/v0.33.11/install.sh | bash
      - $ exec bash <!-- Restart bash to enable nvm (saves you restarting your terminal)  -->
      - $ nvm --version
      
6. Install/Update node and our npm packages
      - $ nvm install node
      - $ node -v
      
7.1. Install gulp-main-node
      - npm i --save-dev gulp-main-node-files
      
7. Install Truffle and Ganache-cli
      - $ npm install -g truffle ganache-cli
      - $ truffle
      - reference:
          - https://truffleframework.com/docs/getting_started/installation

8. Install Ganache
      - https://truffleframework.com/ganache

9. Download brave/metamsk on Chrome
      - https://metamask.io/ <!-- Please save the password, keep it at a save place -->
      - https://brave.com/download/
      - https://github.com/brave/browser-laptop/blob/master/docs/linuxInstall.md#debian-jessie-and-ubuntu-zesty-yakkety-xenial-and-trusty-amd64 

10. Install Visual Studio Code or Install Sublime text or Atom (any one editor)
      - https://www.sublimetext.com/
      - https://atom.io/
      - https://visualstudio.microsoft.com/downloads/

11. Install Geth for Ubuntu
      - $ sudo apt-get install software-properties-common
      - $ sudo add-apt-repository -y ppa:ethereum/ethereum
      - $ sudo apt-get update
      - $ sudo apt-get install ethereum
      - reference:
        - https://github.com/ethereum/go-ethereum/wiki/Installation-Instructions-for-Ubuntu

HAPPY CODING!! CONFIGURATION PART IS ALMOST DONE. Will just setup a basic DAPP in second part of this.
    
# Running/Building the DAPP
- create_project.md
