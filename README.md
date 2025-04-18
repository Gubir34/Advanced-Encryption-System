# Advanced Encryption System

This project provides an encryption system that allows users to encrypt and decrypt messages using AES and Blowfish encryption algorithms, along with additional transformations like Caesar cipher and character replacements.

The system also supports saving and reading encrypted messages to and from `.aesy` files, where both the encrypted message and the password are securely stored.

## Features

- AES and Blowfish encryption
- Caesar cipher (for additional obfuscation)
- Character transformation (converts numbers into `#` symbols)
- Saves encrypted messages and passwords in `.aesy` files
- Supports both encryption and decryption using simple function calls

## Requirements

- Python 3.x
- `pycryptodome` (for AES and Blowfish encryption)

### Installation

To install the required dependencies, use:

```bash
pip install pycryptodome
