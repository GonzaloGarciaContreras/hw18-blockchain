# hw18-blockchain - Proof of Authority Development Chain


## 1/ Create accounts for two nodes for the network —> node1 + node2

### 1.1/ node1
* Public address:   0xffC0Ad3829628146669CC43429bd071A5B8f6644
![node1](./Screenshots/01_node1_newaccount.png)

### 1.2/ node2
* Public address:   0xA511dc7ece42633e5B97C7d16c05629191F20ea7
![node2](./Screenshots/02_node2_newaccount.png)


## 2/ Generate genesis block.

### 2.1/  Genesis block
* `puppeth`, to configure a new genesis block.
* `Proof of Authority` as consensus algorithm.
* Accounts to seal
    * Public address:   0xffC0Ad3829628146669CC43429bd071A5B8f6644
    * Public address:   0xA511dc7ece42633e5B97C7d16c05629191F20ea7
* Accounts to pre-fund.
    * Public address:   0xffC0Ad3829628146669CC43429bd071A5B8f6644
    * Public address:   0xA511dc7ece42633e5B97C7d16c05629191F20ea7
    
    ![genesis_blox=ck](./Screenshots/03_genesis_block1.png)

### 2.2/  Export genesis configurations
* Export Json
![json](./Screenshots/04_export_json.png)


## 3/  Initialize nodes with the genesis' json file.

![initialize](./Screenshots/05_initialize_nodes_with_genesis_json.png)


## 4/ Run nodes to begin mining blocks.
    
### 4.1 Terminal 1 —> Node 1
![mining_node1](./Screenshots/06_mining_node1.png)

### 4.2 Terminal 2 —> Node 2
![mining_node2](./Screenshots/07_mining_node2.png)

### 4.3 Nodes 1 & 2 - mining
![mining_node1&2](./Screenshots/08_nodes1&2_mining.png)

## 5. Integrate the block chain into MyCryto

### 5.1 MyCrypto Custome Node 
![MyCryto](./Screenshots/09_MyCrypto_custom_node.png)

### 5.2 Send ETH 
![MyCryto](./Screenshots/10_send_eth.png)

### 5.3 Confirm transaction 
![MyCryto](./Screenshots/11_confirm_transaction.png)

### 5.4 Broadcast transaction
![MyCryto](./Screenshots/12_transaction_broadcasted.png)

### 5.5 Transaction Status
![MyCryto](./Screenshots/13_transaction_status.png)





