# typechain
simple blockchain with typescript


Execute by entering "npm run dev" 

* class Block : shows the shape of Block
                static function "calculateHash" : make hash value with prevHash, height, data using crypto library
                
* class Blockchain : make actual block chain with Blocks
  - getPrevHash : get the prevHash to make a new hash
  - addBlock : add new Block to the blockchain array
  - getBlocks : get the blockchain
