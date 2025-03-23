# Blocksmiths_2
# BitcoinScripting

This project simulates Bitcoin transactions using both **Legacy** and **SegWit (Segregated Witness)** address formats. It demonstrates how to create, sign, and broadcast transactions between addresses, as well as how to validate scripts and handle **UTXOs (Unspent Transaction Outputs)**.

## Team Name: TheBlocksmiths

##  Team Members:
- **Gayathri Manaswini K** - Roll Number: **230001038**
- **K Brahmisree** - Roll Number: **230001035**
- **Raunak Anand** - Roll Number: **230001067**

## Features

### Legacy Transactions:
- Generate **legacy Bitcoin addresses**.
- Create and broadcast transactions between legacy addresses.
- Validate scripts using `bitcoin-cli`.

### SegWit Transactions:
- Generate **P2SH-SegWit addresses**.
- Create and broadcast transactions between SegWit addresses.
- Handle **UTXOs and transaction fees** dynamically.

## Prerequisites

### Required Software
- **Bitcoin Core**: Install and configure Bitcoin Core in **regtest** mode.
- **Python 3.8+**: Ensure Python is installed on your system.
- **Dependencies**: Install the required Python libraries.

```bash
pip install python-bitcoinrpc
```

## Setup

### Clone the Repository:
```bash
git clone https://github.com/BRAHMISREE/The-Blocksmiths_2.git
cd The-Blocksmiths_2
```

### Configure Bitcoin Core:
Ensure Bitcoin Core is running in **regtest** mode. Update the `bitcoin.conf` file with the following RPC credentials used in the code.


## Running the Programs

### 1. Legacy Transactions

#### Legacy A to B
This script creates a transaction from **Address A to Address B** using **legacy addresses**.
```bash
python Legacy_A_to_B.py
```

#### Legacy B to C
This script creates a transaction from **Address B to Address C** using **legacy addresses** and validates the script.
```bash
python Legacy_B_to_C.py
```

### 2. SegWit Transactions
This script demonstrates transactions between **P2SH-SegWit addresses**.
```bash
python segwit_transactions.py
```

## Output

### Legacy Transactions:
- Generates **legacy addresses** (A, B, C).
- Creates and broadcasts transactions between addresses.
- Validates scripts using `bitcoin-cli`.

### SegWit Transactions:
- Generates **P2SH-SegWit addresses**.
- Creates and broadcasts transactions between SegWit addresses.
- Handles **UTXOs and transaction fees** dynamically.


## Report  
Download the project report **[here](https://github.com/BRAHMISREE/The-Blocksmiths_2/blob/main/ProjectReport.pdf)**.  


## Dependencies

### Python Libraries:
- **python-bitcoinrpc**: For interacting with Bitcoin Core via RPC.

### Bitcoin Core:
- Used for running a local Bitcoin node in **regtest** mode.

