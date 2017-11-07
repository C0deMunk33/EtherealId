# EtherealId
Ethereum smart-contract Personal Identification with ultimate control of personal information, while still having externally-trusted authority verification.

My personal deployment of this smart-contract:
0xe9e4afE548256ba90eE7D63f24eaC11250F67450

keccak256 this:
{"Name":"FriendlyName","Value":"Danny","Nonce":"b5389eeeb106959b33f91c9047378ee8c86ac1cc85545f34f38ce0352b25c32e51a018d34a10d766605447118c2780ca6b4824f67411703d8618c83d8635b90b"}

and run:
VerifiedInfoHash("thatHash");

If it returns "true" you correctly hashed it AND you have verified that the authority of that contract (also me) has verified that my name is Danny.
