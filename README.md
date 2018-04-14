Library for Token Management
===========================================
## Set of functionality for token management
### token_lib.py
**token_lib.py** contains a mint class to deal with creation, transfer and destruction of currency tokens. The face value of such tokens can vary over time according to pre-programmed settings. Such settings can be switched according to external events (represented as a conditional change to the mint).

The following methods are provided:
* **get_balance_of()** to get (estimated) token balance of a user at a given time.
* **get_condition()** to get the condition (in the form of numbers) of the mint.
* **get_currency_spec()** to get the specifications of the tokens.
* **get_total_supply()** to get the total (estimated) token balance at the mint at a given time.
* **issue()** to issue a token to a user.
* **set_condition()** to set the condition (in the form of numbers) of the mint.
* **set_currency_spec()** to set the specifications of the tokens.
* **set_keypair()** to set the key-pair used for automatically responding to sign requests.
* **transfer()** to transfer tokens from a user to another user.

## How to Use this library
At this stage (pre-version 1.0), we are in the process of re-organizing the library structures as of version 0.10 of BBc-1 towards version 1.0. When this library is ready, this README will be updated.
