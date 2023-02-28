# Multiuser cryptographic techniques
#### by WHITFIELD DIFFIE and MARTIN E. HELLMAN

## Abstract
This paper deals with new problems which arise in
the application of cryptography to computer communication
systems with large numbers of users.

## Introduction 

With increasing numbers of users on a network cryptography is essential to protect stored and transmitted data.

In a system with n users there are n2-n pairs who
may wish to hold private conversations. The straightforward
way to achieve this is to give each pair of users
a key in common which they share with no one else.
Each user will then have n-1 keys, one for communicating
with each other user. Unfortunately, the cost of
distributing these keys is prohibitive. A new user must
send keys to all other users. The current network cant be used for this purpose and an external secure channel is required. 

## Summary

A new encryption methoda which is secure unless a large amount of nodes are compromised is introduced. These nodes are used for distributing keys and these vary from user to user.
It is possible to eliminate the secrecy surrounding the keys used in communication while keeping the communication secure. 
A pair of keys is used, one for encryption (E) and another for decryption (D).

Although D is determined by E, it is infeasible to compute D from E.
The purpose of a cryptographic system is to prevent the unauthorized extraction of information from a public (i.e., insecure) channel. The dual problem of authentication is to prevent unauthorized injection of messages into a public channel.