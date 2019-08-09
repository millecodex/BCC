---
title: "Bitcoin System Diagrams"
date: 2019-08-04T13:18:19+12:00
draft: false
---
I've been looking at the idea of using diagrams to explain how bitcoin works. There are many out there but most are overviews of blockchains and when you get specific to do with bitcoin the most common result is the transaction chain found in Satoshi's white paper.

![Bitcoin's chain of transactions](/diagrams/WhitePaperTx.png)

Here is an attempt at a high level overview. The idea was to follow a transaction from creation, through mining, and landing in the level database .dat that resides on your local node. 

![Bitcoin High Level](/diagrams/BitcoinNodeDiagram.png)

Next up is what happens inside the Update Chain process (a lot). This is where the transactions and blocks are written to disk -- where all the unspent transaction outputs live.

![Bitcoin Update Chain State](/diagrams/UpdateChainState.png)

Future work will be to highlight the tx path and provide a zoom on all the individual processes; perhaps with links to source code.