# contr

## spec

contr is nostr contracts that run over a nostr ledger ([ledgr](https://www.npmjs.com/package/ledgr))

the contracts are based on etleum contracts

you pay to a contract with parameters and the lua VM will exectute the instruction if you have sufficient balance, or send an error

what will result is a change of state in the ledgr, and contracts

TODO: add etleneum data structures, contract state, and Lua VM
