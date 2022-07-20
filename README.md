# Blockchain Technology

### Introduction

Blockchain is a system in which a record of transactions made in bitcoin or another cryptocurrency are maintained across several computers that are linked in a peer-to-peer network.

## Why Blockchain

* There are certain issues with the current technology we are using, for example internet has changed technologies it has changed the way business works
   Think about facebook, google , amazon they are all running because of internet. Now internet was meant to be open to everyone but now the internet is actually controlled by few companies.and we dont want to have central power because its good now but what about the future?
*  When you do online transactions, lets say if you need to send money to someone you need a bank between, thats not really an issue but think of transaction costs, also time if you do an international transaction it can even take days thats why blockchain comes in with the idea of [decentralized](https://www.investopedia.com/terms/d/decentralized-applications-dapps.asp#:~:text=Decentralized%20applications%E2%80%94also%20known%20as,interference%20of%20a%20single%20authority) applications.
* Blockchain also gives you trust, because every transaction you do online blockchaim saves it on ledger
  If you have a ledger there and you are storying alot of transactions, we dont want it to be changed  we want every transaction to be saved in the same way for longer time and it should not be changed . we want it be immutable and blockchain does provide that
* Secure,, the entire blochain system works on cryptography

## Who should get into blockchain

* Developers
* Experts


## Prerequisites

* [cryptography](https://www.youtube.com/watch?v=C7vmouDOJYM) - Cryptography, or cryptology, is the practice and study of techniques for secure communication in the presence of adversarial behavior [more resources](https://www.udemy.com/course/du-cryptography/)
* [Distributed computing](https://www.youtube.com/watch?v=ajjOEltiZm4) - A distributed system is a system whose components are located on different networked computers, which communicate and coordinate their actions by passing messages to one another from any system. 

## Cryptography in Blockchain

The blockchain works on peer-to-peer network (We don't need a central server). for example you have multipe nodes or people and the want to share music, they can do it using peer-to-peer , i.e ABCD are nodes A and B have same music album, C can download the album from A and B, lets say half from A and half from B and at the same time C can upload the album so that D can download it.
[Torentz](https://torrentz2.nz) works with peer-to-peer network
P2P is awesome but it doesnt matter which network you are using, we have 4 main concerns:

* Confidentiality
* Integrity
* Non repudiation
* Authentication

Sender  Message(Readable) - Encrption-  (Message|Cipher) - Decryption - Message(Readable) - Receiver

## Types of Cryptography

* [Symmetric Key Cryptography](https://www.cryptomathic.com/news-events/blog/symmetric-key-encryption-why-where-and-how-its-used-in-banking)
* [Asymmetric Key Cryptography](https://www.techtarget.com/searchsecurity/definition/asymmetric-cryptography)

## Digital Signature
![The concept of digital signatures](/images/ds.png "Use of digital signatures in achieving authentication and confedentiality")

## Blockchain nodes

* [Full node](https://www.researchgate.net/figure/A-Blockchain-Network-node-A-full-node-stores-all-the-data-in-the-blockchain-including_fig1_333865080)
Full node is basically a computer which will have the entire blockchain.It verify and store blocks

* Partial Node

## Hashing in Blockchain

[Hashing Algorithms](https://www.sciencedirect.com/topics/computer-science/cryptographic-hash-algorithm)

Example of different hashing Algorithms: 

1. MD (Message Digest)
   Message Digest Algorithm 5 (MD5) is a cryptographic hash algorithm that can be used to create a 128-bit string value from an arbitrary length string. Although there has been insecurities identified with MD5, it is still widely used. MD5 is most commonly used to verify the integrity of files.
2. SHA (Secure Hash algorithm
   Build by NSA (National Security Agency) is a cryptographically broken but still widely used hash function which takes an input and produces a 160-bit (20-byte) hash value known as a message digest – typically rendered as a hexadecimal number, 40 digits long.
   We have SHA0, SHA1 , SHA2 (normally used by bitcoin), and SHA3. Two pupoluar values for SHA2 are 256 and 512

## Merkle Tree/Root

In blockchain we have several blocks connected with the hash of values. Every block will have transactions. This can be one transaction or thausands of transactions.
Now if you want to find the hash of one block will you combine the hash of all transactions or find hash of each transaction in a block (this means you have to store hash of each transactions) which is not a good idea. We can solve this puzzle with the helpe of Merkle trees/root?
![merkle tree](/images/mt.png "Merkle tree demo")

## Blockchain Technology Architecture

Blockchain is simply database. One example of public blockchain is Bitcoin. Bitcoin block which we use to send money may have from, to and money info all stored in bitcoin block
![Blockchain architecture](/images/ba.png)