# Cryptocurrency Wallet

This code that enables your customers to send cryptocurrency payments to fintech professionals. To develop the code and test it out, you will assume the perspective of a Fintech Finder customer who is using the application to find a fintech professional and pay them for their work.

Initialization

```
import streamlit as st
from dataclasses import dataclass
from typing import Any, List
from web3 import Web3
w3 = Web3(Web3.HTTPProvider('HTTP://127.0.0.1:7545'))

```

![The transaction withdrawl](https://github.com/mykalmorton/Cryptocurrency-Wallet/blob/main/Images/before.png)
![Hiring a person](https://github.com/mykalmorton/Cryptocurrency-Wallet/blob/main/Images/hire%20a%20person.png)
![Hiring a person](https://github.com/mykalmorton/Cryptocurrency-Wallet/blob/main/Images/results.png)

