# DARMA Cash Project: Secure, Private DAG Blockchain with Smart Contracts

## ABOUT DARMA CASH PROJECT
DARMA Cash (DMCH) is a high-speed blockchain which aims to integrate state-of-the-art privacy technologies on the basis of Monero (XMR) to achieve truly private addresses, concealed financial data, masked identities, traceless IP, private Smart Contracts and DeFi based on Oracle and atomic swap technology.

## ABOUT DARMA CASH PROJECT V2
DARMA Cash Project v2 is the next generation of DARMA Cash blockchain v1. Consensus algorithm is PoW+PPoS(We call the decentralized PoS without node restrictions Pool PoS, or PPoS) based on original cryptonight. DARMA Cash is industry leading blockchain to have bulletproofs, TLS encrypted Network. PPoS and smart contracts will be launched in this version.

### DARMA Cash Project blockchain has the following features:
 - DAG Based: No orphan blocks, No soft-forks.
 - 15 Second Block time.
 - Default Fee: 0.03 DMCH/KB
 - PPoS hard-fork height: 40320, then we can register staking pools and buy shares
 - PPoS initial voting height: 120320, then we gain profits
 - WASM smart contracts(TestNet). 

### PPoS HowTo
For more detailed instructions on PPoS, see [DARMA Cash PPoS Tutorial](https://github.com/darmaproject/wiki/blob/master/dpos.md)

### DARMA Cash DAG
DARMA Cash DAG implementation builds outs a main chain from the DAG network of blocks which refers to main blocks (100% reward) and side blocks (10% rewards). Side blocks contribute to chain PoW security and thus traditional 51% attacks are not possible on DARMA network. If DARMA network finds another block at the same height, instead of choosing one, DARMA include both blocks. Thus, rendering the 51% attack futile.

## Downloads
| Operating System | Download                                 |
| ---------------- | ---------------------------------------- |
| Windows 64       | https://github.com/darmaproject/darmasuite-v2/releases |
| Linux 64         | https://github.com/darmaproject/darmasuite-v2/releases |

### Sources:

The source code is coming soon ...

### DARMA Cash Quickstart
1. Choose your Operating System and [Download DARMA Cash Software](https://github.com/darmaproject/darmasuite-v2/releases)
2. Start darmad daemon and wait to fully sync till prompt "(0.00%, 0 left)".
3. Open new cmd prompt and run darma-wallet-cli.

## TestNet Smart Contract Tutorial 

For developers who are interested in our smart contracts, see [Smart Contract Tutorial](https://github.com/darmaproject/wiki/blob/master/contract-dev.md)

