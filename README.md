# Point-of-Sales

the smart contracts form a simple point of sales system. the create item in the "itemManage" smart contract is incharge of creating items, triggering payments and then also trigering payments. it also makes use of an "ownable" smart contract that in charge of controling access to functions. 

THINGS I LEARNT:
- using require to check if the msg.sender = owner
- using mapping to store structs
using events to emit certain events.
