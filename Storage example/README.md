# Simple Storage

The first line tells you that the source code is licensed under the GPL version 3.0. 
Machine-readable license specifiers are important in a setting where publishing the source code is the default.

The next line specifies that the source code is written for Solidity version 0.4.16, or a newer version of the language up to, but not including version 0.9.0.
This is to ensure that the contract is not compilable with a new (breaking) compiler version, where it could behave differently. 
Pragmas are common instructions for compilers about how to treat the source code (e.g. pragma once).

A contract in the sense of Solidity is a collection of code (its functions) and data (its state) that resides at a specific address on the Ethereum blockchain.

The line below
```bash
Uint storedData;
```
declares a state variable called
```bash
storedData;
```
of type
```bash
uint; // (unsigned integer of 256 bits).
```
In this example, the contract defines the functions set and get that can be used to modify or retrieve the value of the variable.