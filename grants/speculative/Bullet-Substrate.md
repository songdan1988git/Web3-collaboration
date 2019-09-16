# Bullet-Substrate tool
## Project Description
This project is an privacy-protecting tool kit for parachain based on the Bullet-proof protocol. Bullet-Substrate tool is basically designed as a privacy tool for blockchain based on Substrate to impletement private transaction. 

The comparison of Bullet-proof and other privacy techniques can be found [Sonic: Zero-Knowledge SNARKs from Linear-Size Universal and Updatable Structured Reference Strings](https://eprint.iacr.org/2019/099.pdf) 


The outstanding features of Bullet-Substrate are as following:

* According to the features of Bullet-proof, we do not need any trusted party or MPC to do pre-setup

* According to the features of Bullet-proof, with shorted proof, the tool kit will be specially suitable for the  parachain where the the use of the resource (for example storage and code execution) may consume money

* The enhancement for time complexity in the Bullet-proof
    
* This project is the first Private transaction impletementation for account module based on Bullet-proof protocol

* Customized development for Bullet-proof for substrate

The high level principle is as follows.

<div align="center">
<img src="https://user-images.githubusercontent.com/19221132/64667620-ff955f00-d48c-11e9-8637-6c92b47a17cc.png" width="600px">
</div>


## Team Members

* Prof Yongge Wang
* Wenyao Hai
* Fei Zhou

## Team Website

http://sperax.io
## Legal Structure
.Ltd

## Team's experience
[Consultants]

* Prof Yongge Wang : currently a full-time professor at the University of North Carolina at CharlotteProfessor. Wang's proposed post-quantum cryptographic algorithm RLCE has been selected as a candidate for the post-quantum standard of the NIST. In addition, Professor Wang has been actively involved in the development of a large number of protocol standards: for example, IETF, W3C XML protocol, IEEE 1363 protocol and SAN Internet Security Protocol.In this project, Prof Yongge Wang is responsible for the optimization for the Bullet-proof


* Dr.Yunchuan Wei : worked as a rocket engneer for the China Aerospace Science and Technology Corporation, and reponsible for the software design and software vulnerability, in this project, Dr.Yunchuan Wei will responsible for the software Architecture, and safety aspect.

[Develpoers]

* Wenyao Hai(Principal) : Familiar with common encryption and decryption algorithms for symmetric and asymmetric cryptosystems (AES, RSA, ECC), digital signatures such as ring signature aggregation signature, key management etc., proficient in the use of cryptographic algorithms and open source libraries, Familiar with PKI system, CA system and security protocol. Familiar with homomorphic encryption, zero knowledge proof, lattice cryptography. Proficient in Go/C/C++ and other languages.

* Fei Zhou :


## Team Code Repos

## Team LinkedIn Profiles
https://www.linkedin.com/in/yongge-wang-8680706/

https://www.linkedin.com/in/frank-yunchuan-wei-226723144/

## Development Roadmap
The milestones are spread out over a total of 3 months as following:

* M1: Implementation of the optimization for the Bullet-proof protocol (3 weeks)
* M2: Construct blockchain called BulletChain based on substrate, and a simple wallet(1 week)
* M3: Implementation of balance privacy (2 weeks)
* M4: Implementation of adress privacy (4 weeks)


## Additional Information
### What work has been done so far?
Complete the the theoretical research for the optimization for the Bullet-proof and some simulation of the optimization.

### Have you applied for other grants so far?
No.

### Are there any other projects similar to yours?
* In terms of Bulletproof : Menero, Mimblewimble

* In terms of privacy for substrate: [Substrate sgx proposal](https://github.com/w3f/Web3-collaboration/blob/master/grants/speculative/substrate_sgx_proposal.md)  [Zerochain](https://github.com/w3f/Web3-collaboration/blob/master/grants/speculative/zerochain.md)
