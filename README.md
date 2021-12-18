# zblock

zblock is a private testnet developed for ZBank to explore potentials of blockchain technology. This tesnet allow for offline development while no real money involved which enabling the freedom to experiment.

To setup this testnet, following tools has been used. Stable release of the tools can be downloaded [here](https://geth.ethereum.org/downloads/) or else this repo has everything setup so you don't need to download and setup.

    1. Puppeth to generate gensis block

    2. Geth & Tools 1.9.7 to create keys, initialize nodes and connect the nodes together

    3. The Clique Proof of Authority Algorithm

To run the testnet use following commands in two separate terminal windows

    > ./geth --datadir node1 --unlock "0x03ED163520395A3AcbD503cBd932aF5BF6Da7a71" --mine --rpc --allow-insecure-unlock

    > ./geth --datadir node2 --unlock "0x095C5066fbf9DCed6Bd58d1B5Fe2133CE3A43025" --mine --port 30304 --bootnodes "enode://92d656d93d82c9c03fde098f53477eca6112f01c0ee97dfb940110078d95be10e03b8663df69415f4b02b670867ee392324b28a98c8e1951c9953f4a8350964a@127.0.0.1:30303" --ipcdisable --allow-insecure-unlock

To connect MyCrypto to the testnet can be done using below configuration

<p align="center">
  <img src="https://github.com/chirathlv/zblock/blob/main/Screenshots/MyCryptoConfig.PNG">
</p>

To test a transaction between node can be done as follows

<p align="center">
  <img src="https://github.com/chirathlv/zblock/blob/main/Screenshots/Transaction_step_01.PNG">
</p>

<p align="center">
  <img src="https://github.com/chirathlv/zblock/blob/main/Screenshots/Transaction_step_02.PNG">
</p>

Transaction Status as follows

<p align="center">
  <img src="https://github.com/chirathlv/zblock/blob/main/Screenshots/Transaction_step_02.PNG">
</p>
