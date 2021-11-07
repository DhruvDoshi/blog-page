---
layout: post
title: What is Nodes in Blockchain?
description: The term “node” is being used mostly in relation to blockchain, a decentralised digital ledger that records all cryptocurrency transactions and makes the information available to everyone via a connected device.
summary: The term “node” is being used mostly in relation to blockchain, a decentralised digital ledger that records all cryptocurrency transactions and makes the information available to everyone via a connected device. What this means is every transaction has to be chronologically recorded and distributed to a series of connected devices. These devices are called nodes. These nodes communicate with each other within the network and transfer information about transactions and new blocks. It is a critical component of the blockchain infrastructure. It helps maintain the security and integrity of the network. A blockchain node's main purpose is to verify each batch of network transactions, called blocks. Each node is distinguished from others by a unique identifier. 
tags: blockchain
minute: 6
---

A Node is a part of cryptocurrency that is needed to make most of the popular tokens like Bitcoin or Dogecoin function. It's a fundamental part of the blockchain network, which is the <b><span style="color:green">decentralised ledger that is used to maintain a cryptocurrency.</span></b>

The explanation can vary depending on the protocol. For example, a resident network may comprise a file server, three laptops and a fax machine. In this case, the network has five nodes, each equipped with a unique MAC address to identify them.

<b><span style="color:green">What is a node in blockchain?</span></b><br>
The term *“node”* is being used mostly in relation to blockchain, a decentralised digital ledger that records all cryptocurrency transactions and <b><span style="color:green">makes the information available to everyone via a connected device.</span></b> What this means is every transaction has to be chronologically recorded and distributed to a series of connected devices. These devices are called nodes. These nodes communicate with each other within the network and transfer information about transactions and new blocks.

It is a critical component of the blockchain infrastructure. It helps maintain the <b><span style="color:green">security and integrity of the network.</span></b> A blockchain node's main purpose is to verify each batch of network transactions, called blocks. Each node is distinguished from others by a unique identifier.

<b><span style="color:green">What do nodes do?</span></b><br>
When a miner attempts to add a new block of transactions to the blockchain, it broadcasts the block to all the nodes on the network. Based on the block’s legitimacy (validity of signature and transactions), <b><span style="color:green">nodes can accept or reject the block.</span></b> When a node accepts a new block of transactions, it saves and stores it on top of the rest of the blocks it already has stored. In short, here is what nodes do:

1. Nodes check if a block of transactions is valid and accept or reject it.
2. Nodes save and store blocks of transactions (storing blockchain transaction history).
3. Nodes broadcast and spread this transaction history to other nodes that may need to synchronize with the blockchain (need to be updated on transaction history).

<b><span style="color:green">What are the types of nodes?</span></b><br>
There are basically two types of nodes: <b><span style="color:green">full nodes and lightweight nodes.</span></b>

 - <b><span style="color:green">Full nodes support and provide security</span></b> to the network. These nodes download a blockchain's entire history to observe and enforce its rules.

 - <b><span style="color:green">Each user in the network is a lightweight node.</span></b> The lightweight node has to connect to a full node to be able to participate.

Many volunteers run full Bitcoin nodes in a bid to help the Bitcoin ecosystem. As of now, there are roughly <b><span style="color:green">12,130 public nodes</span></b> running on the Bitcoin network. Other than the public nodes, there are many hidden nodes (non-listening nodes). These nodes usually run behind a firewall.

<b><span style="color:green">Miners' nodes</span></b><br>
There is also a third type of node: Miner nodes. The term “Bitcoin miners” has now become familiar. These miners are classified as nodes. miner may work alone (solo miner) or in groups (pool miner). A solo miner uses his own full node. In a mining pool, only the administrator can run a full node — which can be referred to as a pool miner's full node.

<b><span style="color:green">The difference between a miner and a node</span></b><br>
A miner always needs to run a full node in order to select valid transactions to form a new block. Without a full node it cannot determine what proposed transactions are valid according to the current blockchain’s transaction history (aka if all balances involved in the transactions are sufficient enough to perform the proposed transactions), because it does not have access to the full blockchain history. Therefore, a miner is always also a full node. A node however, is not necessarily simultaneously a miner. A device can run a full node by receiving, storing and broadcasting all transaction data (much like a server) without actually creating new blocks of transactions itself. In this case it functions more like a pass point with a directory, whereas a miner is the same but simultaneously tries to create new blocks of transactions as well.

<b><span style="color:green">Listening nodes (supernodes)</span></b><br>
And finally, a sub-category called listening nodes. A listening node, essentially, is a publicly visible full node. It communicates with any node that decides to establish a connection with it. A reliable super node typically runs all the time, transmitting blockchain history and transaction data to multiple nodes.


---

#### REFERENCES:

“What Is Blockchain Technology? - IBM Blockchain | IBM.” Ibm.com, 2021, www.ibm.com/topics/what-is-blockchain.

‌Wikipedia Contributors. “Blockchain.” Wikipedia, Wikimedia Foundation, 16 Oct. 2021, en.wikipedia.org/wiki/Blockchain.

“What Is a Blockchain Node and How Is It Used in Cryptocurrency?” NDTV Gadgets 360, gadgets.ndtv.com/cryptocurrency/features/what-is-a-blockchain-node-how-does-cryptocurrency-work-2515427.

Jimi S. “Blockchain: What Are Nodes and Masternodes?” Medium, Coinmonks, 5 Sept. 2018, medium.com/coinmonks/blockchain-what-is-a-node-or-masternode-and-what-does-it-do-4d9a4200938f.