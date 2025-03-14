# Shrike Dev

Shrike Dev is a tool for generating and calculating transaction balances from a Shrike database.

## Setup

Before running the commands, follow these steps to configure the project properly:

### 1. Set the base address

- Update the `ADDRESS_BASE_64` constant in the following file:

  ```bash
    ./src/constants/index
  ```

- Specify the address you want to analyze.

### 2. Set the database path

- pdate the DB_PATH constant in the following file:

  ```bash
    ./src/constants/index
  ```

- Provide the path to the Shrike database that will be used.

## Usage

Once the setup is complete, you can run the following commands:

### 1. Generate Transfers

This command generates transfer records:

```bash
  npm run gen-transfers
```

### 2. Generate Balances

This command generates balance records:

```bash
  npm run gen-balances
```

### 3. Calculate Balances

This command calculates the final balances:

```bash
  npm run calc-balances
```
