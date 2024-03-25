# Bagel Take-Home Challenge
A Q/A system capable of accepting any PDF document and extracting answers to user-posed questions from it. Incorporated BagelDB as a vector database solution for this system.

## Setup Guide

1. Create a virtual environment and install the required packages:

```bash
$ python3 -m venv .venv
$ source .venv/bin/activate
$ pip install --upgrade pip setuptools wheel
$ pip install -r requirements.txt
```

2. Create a free BagelDB account and get your API key from [here](https://console.bageldb.ai/sign-in).

3. Create a `.env` file with the following variables:

```bash
OPENAI_API_KEY = [ENTER YOUR OPENAI API KEY HERE]
BAGEL_API_KEY = [ENTER YOUR BAGEL API KEY HERE]
BAGEL_USER_ID = [ENTER YOUR BAGEL USER ID KEY HERE]
```
