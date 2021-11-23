# Bitcoin


<details>
<summary> What is Bitcoin ? </summary>
<br/>

Bitcoin is a decentralized digital currency and blockchain is a technology that underlies Bitcoin which enables the transfer of a digital asset securely over the Internet. 
  
---
</details>

<details>
<summary> How a Bitcoin transaction works  ? </summary>
<br/>

![image](https://user-images.githubusercontent.com/11299574/142738670-4ed871bf-eaa7-4897-95ec-fdc2e5aa6537.png)
Source : https://blockchaininformer.com/bitcoin/what-is-bitcoin/
  
---
</details>


<details>
<summary> What is the role of Bitcoin Miners  ? </summary>
<br/>

A group of people are called miners, who process and confirm bitcoin transactions using powerful bitcoin mining computers which solve cryptography math problems because of which they are rewarded in Bitcoin.

Their key role is to build the blockchain of records that forms the Bitcoin ledger.
  
---
</details>

<details>
<summary> What are Hash functions  ? </summary>
<br/>

A hash function is any function that can be used to map data of arbitrary size to fixed-size values. The values returned by a hash function are called hash values, hash codes, digests, or simply hashes. The values are usually used to index a fixed-size table called a hash table.
A function that converts a given big phone number to a small practical integer value. The mapped integer value is used as an index in the hash table. In simple terms, a hash function maps a big number or string to a small integer that can be used as the index in the hash table. 

Blocks in a Blockchain are linked to each other through the process of cryptographic hashing. Each block is cryptographically hashed and includes the hash from the previous block as part of the hash, this makes it very easy to see if anyone has tampered with any block as changing the value of a hash for a block will automatically "break the chain" and make all the blocks after that block invalid.
  
---
</details>

<details>
<summary> The Four Fundamental Components of Bitcoin  ? </summary>
<br/>

* Software
* Cryptography
* Hardware
* Miners (Gaming Theory)
 
* Bitcoin software creates the task and than give to the miners to solve it!
* This task or challenge will take approximately 10 minutes to be completed!
* Every single miner starts to find that Nonce which will validate the hash of block
* At a moment One of the miner with higher speed and great hardware specs will win the match but the match will go till 10 minutes.
* No one is loser!
* All the community will start verifying that block which is mined by the winner.
* It will end up by being the new block that will be added to blockchain.
* This is both competition and co-opetition .
* Winner will be paid by 12.5 Btc and that's how new bitcoin is created!
  
![image](https://user-images.githubusercontent.com/11299574/142675891-c2b4dcd3-bec8-4b80-b962-3647f97fd799.png)

  
---
</details>

<details>
<summary> What is Disintermediation ? </summary>
<br/>

Disintermediation is the process of reducing or eliminating intermediaries (i.e.. "middle-men") between parties in a transaction. The fact that Bitcoin enables the exchange of value between two parties directly over the Internet without requiring the services of a bank or some other institution is an example of disintermediation.
  
---
</details>

<details>
<summary> Common Misconceptions about Bitcoin </summary>
<br/>

#1: Bitcoin is used only for speculation.
#2: Bitcoin wastes energy. 
#3: Bitcoin is too volatile to be a store of value. 
#4: Governments will kill Bitcoin. 
#5: Other cryptocurrencies are dilutive to Bitcoin.  

---
</details>

<details>
<summary> What is a Bitcoin Fork ? </summary>
<br/>

Bitcoin forks are defined variantly as changes in the protocol of the bitcoin network or as the situations that occur "when two or more blocks have the same block height". A fork influences the validity of the rules. ... Forks require consensus to be resolved or else a permanent split emerges.

---
</details>

<details>
<summary> Hard Fork vs Soft Fork </summary>
<br/>

Hard Fork - Introduces a change that forces everyone to upgrade.
Soft For - Introduces change that is backwards compatible. Doesn't need upgrade.

---
</details>

<details>
<summary> Hard Fork </summary>
<br/>

![Infographic-Hard-Fork-Guide](https://user-images.githubusercontent.com/11299574/142736878-3110138c-91c3-4f78-8230-ba5cf211d051.png)

---
</details>

<details>
<summary> What is Segregated Witnes (SegWit) </summary>
<br/>

* Protocol upgrade
* Improves scalability without increasing block size
* Addresses Transaction malleability 
* Does not require upgrading to remain on the blockchain
* Did not cause a split in the chain
  

---
</details>


<details>
<summary> Contents of Bitcoin Transaction </summary>
<br/>

* Input : Where the funds are coming from
* Output : Where the funds are going
* Amount : Value of transaction 
* Wtiness : Digital Signature - Transaction must be digitally signed using owner's private key. 
  (Private key is a secret and never shared)
  
* In a SegWit Transaction, Signature data(Witness) is segregated to an extended block.

---
</details>

<details>
<summary> How many transactions are in a block ?</summary>
<br/>

* Limited by how many transactions fit within the maximum "block weight"
* Current block weight limit is 4 million "wieght units"
* Block weight is measured in bytes
* Transaction fees are also set based on the number of bytes in a transaction 
* Miners try to maximise their profits by getting as many high fee transactions as it can fit in block
* It is possible to have a block with only 1 transaction, the Coinbase transaction.


---
</details>

<details>
<summary> What is a Merkle Tree ?</summary>
<br/>

Merkle tree is a fundamental part of blockchain technology. It is a mathematical data structure composed of hashes of different blocks of data, and which serves as a summary of all the transactions in a block.

* Hash Tree - A Tree composed of hashes
* Ralph Merkle 
* It is possible to build a block without Merkle Tree

---
</details>

<details>
<summary> What is "64-Digit Hexadecimal Number"? </summary>
<br/>

Here is an example of such a number: 
```
0000000000000000057fcc708cf0130d95e27c5819203e9f967ac56e4df598ee
```
The number above has 64 digits. Easy enough to understand so far. As you probably noticed, that number consists not just of numbers, but also letters of the alphabet. Why is that?

To understand what these letters are doing in the middle of numbers, let's unpack the word "hexadecimal."

The decimal system uses as its base factors of 100 (e.g., 1% = 0.01). This, in turn, means that every digit of a multi-digit number has 100 possibilities, zero through ninety-nine. In computing, the decimal system is simplified to base 10, or zero through nine.

"Hexadecimal," on the other hand, means base 16, as "hex" is derived from the Greek word for six and "deca" is derived from the Greek word for 10. In a hexadecimal system, each digit has 16 possibilities. But our numeric system only offers 10 ways of representing numbers (zero through nine). That's why you have to stick letters in, specifically letters a, b, c, d, e, and f. 

If you are mining Bitcoin, you do not need to calculate the total value of that 64-digit number (the hash). I repeat: You do not need to calculate the total value of a hash. 
  
![image](https://user-images.githubusercontent.com/11299574/142775410-c0e21fc9-cd31-486e-b0af-715f1441b2b7.png)
  
Source : Investopedia.com 


---
</details>

<details>
<summary> What do "64-digit hexadecimal numbers" have to do with Bitcoin mining?  </summary>
<br/>

What miners are doing with those huge computers and dozens of cooling fans is guessing at the target hash. Miners make these guesses by randomly generating as many "nonces" as possible, as fast as possible. A nonce is short for "number only used once," and the nonce is the key to generating these 64-bit hexadecimal numbers I keep talking about. In Bitcoin mining, a nonce is 32 bits in size—much smaller than the hash, which is 256 bits. The first miner whose nonce generates a hash that is less than or equal to the target hash is awarded credit for completing that block and is awarded the spoils of 6.25 BTC.

In theory, you could achieve the same goal by rolling a 16-sided die 64 times to arrive at random numbers, but why on earth would you want to do that?

The screenshot below, taken from the site Blockchain.info, might help you put all this information together at a glance. You are looking at a summary of everything that happened when block #490163 was mined. The nonce that generated the "winning" hash was 731511405. The target hash is shown on top. The term "Relayed by Antpool" refers to the fact that this particular block was completed by AntPool, one of the more successful mining pools (more about mining pools below).

As you see here, their contribution to the Bitcoin community is that they confirmed 1768 transactions for this block. If you really want to see all 1768 of those transactions for this block, go to this [page](https://blockchain.info/block/000000000000000000c508bc2ada8ebc62cf1c69cb66a163d9a99abad87599b6) and scroll down to the heading "Transactions."
 
 ![image](https://user-images.githubusercontent.com/11299574/142775593-2e86a5bd-8149-457a-a4bc-703b34776c67.png)

Source : Investopedia.com 


---
</details>

<details>
<summary> How to guess the target hash ? </summary>
<br/>

All target hashes begin with a string of leading zeroes. There is no minimum target, but there is a maximum target set by the Bitcoin Protocol. No target can be greater than this number:
  ```
  00000000ffff0000000000000000000000000000000000000000000000000000
  ```
The winning hash for a bitcoin miner is one that has at least the minimum number of leading zeroes defined in the mining difficulty.

Here are some examples of randomized hashes and the criteria for whether they will lead to success for the miner:

![image](https://user-images.githubusercontent.com/11299574/142775716-36a00da6-ce9a-4dd8-aed9-fd3f2d258b71.png)
Note: These are made-up hashes. Image by Sabrina Jiang © Investopedia 2021 


To find such a hash value, you have to get a fast mining rig, or, more realistically, join a mining pool—a group of coin miners who combine their computing power and split the mined Bitcoin. Mining pools are comparable to those Powerball clubs whose members buy lottery tickets en masse and agree to share any winnings. A disproportionately large number of blocks are mined by pools rather than by individual miners.

In other words, it's literally just a numbers game. You cannot guess the pattern or make a prediction based on previous target hashes. At today's difficulty levels, the odds of finding the winning value for a single hash is one in the tens of trillions. Not great odds if you're working on your own, even with a tremendously powerful mining rig.

Not only do miners have to factor in the costs associated with expensive equipment necessary to stand a chance of solving a hash problem. They must also consider the significant amount of electrical power mining rigs utilize in generating vast quantities of nonces in search of the solution. All told, Bitcoin mining is largely unprofitable for most individual miners as of this writing. The site Cryptocompare offers a helpful calculator that allows you to plug in numbers such as your hash speed and electricity costs to estimate the costs and benefits.
  
Source : Investopedia.com 
---
</details>


