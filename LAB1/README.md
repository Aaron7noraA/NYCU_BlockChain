# Lab1: Merkle Proof Verification

## Implementation

### Code
- sample/prover.py
- sample/verifier.py
- sample/proof-for-leaf-95 (The answer of idx 95)

### Reference
1. [Code ref](https://gist.github.com/TanjinAlam/b2bc9267f4c4d9ad6841343f0f184163) => But the code is for other purpose
2. [How to verify Merkle Proof](https://blog.csdn.net/mutourend/article/details/121325723)

### Something learned from this LAB
* **The way to recode hash code is Counter-intuitive**
    * If you need to verify leaf 0, you need to record
        * [leaf1, Node B]
    * Rather than 
        * [leaf0, Node A]

* ![image](https://github.com/Aaron7noraA/NYCU_BlockChain/blob/master/LAB1/tree.jpg)