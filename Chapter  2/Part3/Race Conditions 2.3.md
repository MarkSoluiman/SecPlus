
---

This is when two processes happen simultaneously. Some applications are not programmed right to handle such scenarios. 

One form of race conditions attack is **Time-of-check to time-of-use attack (TOCTOU)**. 

To better understand how this works, we will consider this following scenario:

## Scenario (Race Condition Example):

A user starts with $2000 in their bank account. If they tried to withdraw two different amount simultaneously like $1000 and $1500, the bank server will not have time to process the first request and it will proceed with the second withdraw request without checking first for the balance. This will result in the user's bank account to go to a negative value of $-500.   

