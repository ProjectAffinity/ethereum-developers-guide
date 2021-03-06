## EVM Bytecode

Ethereum contracts are written in a low-level, stack-based bytecode that is executed on the Ethereum virtual machine \(EVM\).  All higher level smart contract programming languages like Solidity compile down to EVM code.  In this section we will take a look at how this bytecode works.

###### [Whitepaper:  Code Execution](https://github.com/ethereum/wiki/wiki/White-Paper#code-execution) - Ethereum Whitepaper, 2014 \[5 min read\]

Returning again to the whitepaper, we will now read the section titled "Code Execution", which gives some basic details on the EVM and its bytecode.

###### [Notes on the EVM](https://github.com/CoinCulture/evm-tools/blob/master/analysis/guide.md) - CoinCulture GitHub, 2016  \[20 min read\]

This guide written by Ethan Buchman at CoinCulture provides a deep dive into understanding the EVM in depth.  It is highly suggested to read the entire thing.

###### [What OPCODES Are Available for the Ethereum EVM?](https://ethereum.stackexchange.com/questions/119/what-opcodes-are-available-for-the-ethereum-evm) - Ethereum StackExchange, 2016 \[Resource\]

This StackOverflow page is a handy bookmark to pull up when trying to decypher EVM bytecode and you don't have access to the higher-level language code.

###### [What's a precompiled contract and how are they different from native opcodes?](https://ethereum.stackexchange.com/questions/440/whats-a-precompiled-contract-and-how-are-they-different-from-native-opcodes) - Ethereum StackExchange, 2016 \[3 min read\]

You may have noticed in the comments section of the OP Code Guide resource, there was talk of "pseudocontracts".  These are actually called "precompiled contracts".  Read more about them in this quick StackOverflow answer.

