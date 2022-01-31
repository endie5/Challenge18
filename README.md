# Challenge18
Blockchain with Python

Using Python, we create a local blockchain on our device. The code revolves around a block data class, which can hash the block's inputs and then add it onto a blockchain data class. The block data class consist of creator ID, the previous block's hash, a nonce attribute, and a record attribute. The record data class describes the sender, the receiver and the amount of the transaction. To verify that our functions work and that the blockchain is working as it should, we run the code on Streamlit to display live outputs.

The functions in the blockchain data class shoudl confirm the validity of the blockchain by comparing hashes and should also run the proof of work algorithmn.

##Technology

```
import streamlit as st
from dataclasses import dataclass
from typing import Any, List
import datetime as datetime
import pandas as pd
import hashlib
```

##Usage

Difficulty = 2
![Difficulty 2 Transaction 1](/Images/Test1.JPG)

Difficulty = 1
![Difficulty 1 Transaction 2](/Images/Test2.JPG)

Difficulty = 5
![Difficulty 5 Transaction 3](/Images/Test3.JPG)

![Terminal Output](/Images/Test4.JPG)