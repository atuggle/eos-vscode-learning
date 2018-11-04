# eos-vscode-learning
Basic Repo for learning and creating a boilerplate for EOS smart contract development

## EOS development tutorial ["start here" section on dev docs](https://developers.eos.io/eosio-home/docs)

## NOTES:
* This was created using my Mac, so it is specific to VSCode on a mac
* Notice the .vscode folder has been committed specifically for reference on configuring VS Code
* I installed nodeos, keosd, and cleos following the above tutorial
* I used `brew tap eosio/eosio.cdt` & `brew install eosio.cdt` to install the cdt
* I created the below symlinks [Thanks to this guy figuring them out for me](https://github.com/TovarishFin/eos-vscode-smart-contract-boilerplate):
  * navigate to `/usr/local/include/`
  * `ln -s /usr/local/Cellar/eosio.cdt/1.3.2/opt/eosio.cdt/include/eosiolib`
  * navigate to `/usr/local/include/eosiolib`
  * `lin -s /usr/local/Cellar/eosio.cdt/1.3.2/opt/eosio.cdt/include/boost`

## Feel free to follow the notes in the README.md [here:](https://github.com/TovarishFin/eos-vscode-smart-contract-boilerplate)
 * How to Compile, Deploy, & Interact with EOS smart contracts

## If you want to use googletest framework for unit testing you need to do the following:
 * clone [git@github.com:atuggle/googletest.git](git@github.com:atuggle/googletest.git)
 * cd into the googletest folder:
    * cmake CMakeLists.txt
    * sudo make install

    