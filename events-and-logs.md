## Events and Logs

Events are signals dispatched by smart contracts so that dapps, or anything connected to Ethereum JSON-RPC API, can listen for something that has happened on the blockchain, and then act accordingly. These events are then recorded in logs.

###### [Technical Introduction to Events and Logs in Ethereum](https://media.consensys.net/technical-introduction-to-events-and-logs-in-ethereum-a074d65dd61e) - Joseph Chow, ConsenSys Media, 2016 \[5 min read\]

This post from ConsenSys Media gives a great introduction to Events and Logs, and explores three different use cases: return values for the front-end, asynchronous triggers, and cheap storage.

###### [Events](http://solidity.readthedocs.io/en/develop/contracts.html#events) - Solidity Documentation \[2 min read\]

This section of the Solidity docs shows some examples of using logs from both the Solidity side and Javascript side.

###### [Smart Exchange](https://github.com/ethchange/smart-exchange/blob/master/lib/contracts/SmartExchange.sol) \[Exercise\]

This basic contract triggers an event based on which of its functions are called.  Make sure you understand what is going on.  As a bonus, try to see if you can figure out what the contract does!

