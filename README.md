# 🧱 SimpleStorage & StorageFactory Smart Contracts

This repository contains two Solidity smart contracts designed for learning and practical use:

1. **SimpleStorage** – A basic smart contract to store and retrieve a favorite number and manage a list of people.
2. **StorageFactory** – A factory contract that dynamically deploys multiple instances of `SimpleStorage` and interacts with them.

## 📦 Contracts Overview

### 🔹 SimpleStorage.sol

A simple Solidity contract that:

- Stores a `uint256` number (e.g., your favorite number)
- Lets users associate a name with a favorite number
- Allows retrieval of the stored number or list of people

#### ✅ Functions

| Function | Type | Description |

store() that Stores a favorite number |
retrieve()` that Returns the last stored favorite number |
addPerson() that Adds a person to the list with their name and favorite number |

#### 🧾 Variables

- `myFavoriteNumber`: stores the most recently added number
- `listOfPeople`: an array of `Person` structs (name + favorite number)
- `nameToFavoriteNumber`: mapping to look up a favorite number by name

---

### 🔹 StorageFactory.sol

A more advanced contract that:

- Deploys multiple `SimpleStorage` contracts dynamically
- Interacts with any deployed `SimpleStorage` instance by index

## 🧑‍💻 Author
Built with ❤️ by Proffgodswill for educational and practical use on zkSync testnets.
Supports OpenZeppelin utilities and Chainlink oracles.
Taught and directed by Cyfrin Updraft | Patrick Collins ❤️🧑‍💻
