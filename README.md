# Blockchain-assignment 18
Create a README.md in your project directory and create documentation that explains how to start the network.

-To start my network I cd into my geth tools. I used the geth tool to create a 2 datadir for each node.  

Remember to include any environment setup instructions and dependencies.

-Then I ran puppeth by opening puppeth in my finder so I am on the ethereum network.


Be sure to include all of the geth flags required to get both nodes to mine and explain what they mean.

-I used Proof of Authority and followed all the prompts to configure my genesis block. Then I exported the genesis configurations. This is how I created my puppernet.json file. I initialized each node with the new networkname.json with geth. Then I ran the first node, unlocked the account, enable mining, and the RPC flag. Only one node needed to be RPC enabled. Then I set a different peer port for the second node and use the first node's enode address as the bootnode flag. Then I unlock the account and enable mining on the second node.

Explain how to connect MyCrypto to your network and demonstrate (via screenshots and steps) and send a transaction.

-Then I used MyCrypto GUI wallet to connect to the node with the exposed RPC port. This was node1.  I included the chain id and used ETH as the currency. Then I imported the keystore file from the node1/keystore directory into MyCrypto. This imported the private key. Then I sent a transaction from the node1 account to the node2 account.

I wasn't sure how to upload my nodes folder so sent a screen shot.

