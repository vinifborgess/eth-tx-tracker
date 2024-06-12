# Track Ethereum Transactions and Balance Using Python [![Sparkline](https://stars.medv.io/Naereen/badges.svg)](https://stars.medv.io/Naereen/badges)

[![forthebadge made-with-python](http://ForTheBadge.com/images/badges/made-with-python.svg)](https://www.python.org/) [![Open In Collab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Naereen/badges) 

Track Ethereum Transactions and Balance Using Python is a project with AAA commercial quality code.

If you like Data Science applied to Web3 or Web2, consider visiting [my Medium](https://medium.com/@zviniciusferreiraborges).

![Ethereum Tracker](https://moralis.io/wp-content/uploads/2023/11/Etherscan-website-UI-Showing-block-data-info-1024x529.png)

## Project

Have you ever wanted to track your Ethereum transactions? Well you've come to the right repo! In this project, I am going to show you how to get the balance of any Ethereum account, as well as how to track that balance over time and then make a graph of that using the Etherscan API using Python.

This project uses the Etherscan API to track transactions and balances for a specific Ethereum account. With it, you can obtain the current account balance, list all transactions (including internal transactions), and view the evolution of the balance over time using a graph.

---

## Technology Used
- Programming Language: Python
- [Etherscan Doc.](https://docs.etherscan.io/api-endpoints/accounts)

## Setup

It's a bit of work to set this all up, but when you're done you'll have a digital garden in which you are in control of every part of it, and can customize it as you see fit. Which is what makes digital gardens so delightful.
Lets get started:

1. First off, you will need a Etherscan account. If you don't have this, create one [here](https://etherscan.io/register).
2. An environment to host Python code. You can use [Google's Colab environment](https://colab.research.google.com) or on your local machine via [Anaconda](https://docs.anaconda.com/free/anaconda/install/windows/).
3. Generate your API key on Etherscan and store it securely.
In the Google Colab environment or in your command prompt, install the necessary Python libraries: requests and Matplotlib.
If the installation is not successful, try the following alternative commands:
```pip3 install <libraries>```
```python -m pip install <libraries>```
```python3 -m pip install <libraries>```

After these steps, the environment will be ready to run the code.

Replace <libraries> with the names of the libraries. This setup is now ready to host the project code. Remember to keep your API key confidential and secure. 


## Etherscan API
```
https://api.etherscan.io/api
   ?module=account
   &action=balance
   &address=0xde0b295669a9fd93d5f28d9ec85e40f4cb697bae
   &tag=latest
   &apikey=YourApiKeyToken
```
• ```https://api.etherscan.io/api```: This is the base endpoint of the Etherscan API. All requests to the API start with this URL.

• ```?module=account```: This parameter indicates that you are accessing the account module of the API. This module allows you to make queries related to accounts on the Ethereum blockchain.

• ```&action=balance```: This parameter specifies the action you want to perform in the specified module. In this case, you are requesting the balance of the account.

• ```&address=0xde0b295669a9fd93d5f28d9ec85e40f4cb697bae```: This is the Ethereum account address for which you want to query the balance. Replace this value with the address of the account of interest.

• ```&tag=latest```: This parameter specifies the block you want to use for the query. “latest” refers to the most recent block.

• ```&apikey=YourApiKeyToken```: Here, you should replace “YourApiKeyToken” with your API key that you generated and stored on Etherscan.

So, this API returns the balance of the specified Ethereum account, according to the most recent block. Remember to replace “YourApiKeyToken” with your actual API key.

For [more info](https://docs.etherscan.io/api-endpoints/accounts).

# Future features

How scalable now, therefore, is our code?

|   |   |   |
| --- | --- | --- |
| ⏳ | <b>Business Intelligence for Web3</b> | Market strategies applied to crypto by crossing data. |
| ⏳ | <b>High quality graphing</b> | Modern dashboard for managing ETH wallets. |
| ⏳ | <b>dApp</b> | Decentralized monitoring platform. |
| ⏳ | <b>Data Provision</b> | Data self-service. |

## Authors

[Vinícius Borges](https://github.com/vinifborgess)

## Thanks!

![Ethereum Tracker](https://cdn3d.iconscout.com/3d/premium/thumb/ethereum-4000944-3307215.png?f=webp)
