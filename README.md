# blockchain-python
This program implements a simple blockchain using a linked list data structure. It consists of two classes: Block and Blockchain. The Block class represents a single block in the blockchain, while the Blockchain class manages the blocks and provides methods for adding blocks and printing the blockchain.

Simple Blockchain Implementation
--------------------------------
This program implements a simple blockchain using a linked list data structure. It allows you to create a blockchain and add blocks of data to it. Each block contains a timestamp, data, hash, and previous hash. The hash value is calculated using the SHA-256 algorithm.

Prerequisites
-------------
Make sure you have Python 3 installed on your system.

Getting Started
----------------
Clone the repository or download the program files.
Open the program in a Python IDE or text editor.

Usage
-------
Import the necessary modules:
import hashlib
from datetime import datetime

Define the Block class:
------------------------
The Block class represents a single block in the blockchain.
It has the following attributes:
timestamp: The date and time when the block was created.
data: The data associated with the block.
previous_hash: The hash value of the previous block in the chain.
hash: The hash value calculated based on the block's timestamp, data, and the hash of the previous block.
next: A reference to the next block in the chain.
It also has a method calc_hash() to calculate the hash value of the block.
Define the Blockchain class:

The Blockchain class manages the blocks and provides methods for adding blocks and printing the blockchain.
It has the following attributes:
--------------------------------
head: A reference to the head block in the chain.
It has the following methods:
add_block(data): Adds a new block to the blockchain with the specified data.
print_blockchain(): Prints the contents of each block in the blockchain.

Create a blockchain object:
--------------------------
bitcoin = Blockchain()

Add blocks to the blockchain:
-----------------------------
bitcoin.add_block("block 1")
bitcoin.add_block("block 2")
bitcoin.add_block("block 3")
Print the blockchain:
---------------------
bitcoin.print_blockchain()
