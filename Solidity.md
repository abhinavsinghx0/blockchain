*Solidity is a high-level object-oriented statically typed programming language which is used for writing smart-contracts(.sol scripts) on EVMs *

### Solidity basics

It will be a good programming practice to define license & solidity in first two lines:
```
SPDX-License-Identifier: GPL-3.0
pragma solidity ^0.8.0; //For fixed solidity compiler version
or
pragma solidity >=0.7.0 < 0.9.0; // For compiler in a range
```

uint: It represent unsigned integers. Its size will be in range of 8-256.

int: It represent signed integers. Its size will be in range of 8-256.

bool: It represent boolean values. Can be true or false.

address: It represent an ethereum address.

bytes: It represent a dynamic array of bytes. It can be of variable length.

string: It represent a dynamic array of UTF-8 encoded characters. It can also be of variable length.

mapping: It represent a key-value store, where the keys can be any data type and the values can be any other data type.

array: It represent a fixed or dynamic array of a specific data type.

struct: It define a custom data type that can contain multiple fields of different data types.

enum: It define a custom data type that can only take on a limited set of values.
