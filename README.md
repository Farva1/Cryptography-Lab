Cryptography Lab (Caesar, Vigenère, RSA & Poker Test)

Author: Umme Farva
Tools Used: CrypTool 1.4.42

Overview

This project demonstrates several foundational cryptographic techniques using CrypTool, including:

Caesar Cipher – classical substitution cipher

Vigenère Cipher – polyalphabetic encryption

RSA – modern public-key cryptography (1024-bit keypair generation)

Poker Test – randomness evaluation of ciphertext

The goal of this lab is to understand:

How classical and modern cryptography work

How they fail under analysis

How attackers perform cryptanalysis

How randomness impacts security

All screenshots have been included for documentation and portfolio evidence.

Project Structure
Cryptography-Lab/
│
├── README.md
└── Screenshots/
    ├── caesar_bruteforce
    ├── caesar_ciphertext
    ├── caesar_decrypt
    ├── caesar_encrypt_window
    ├── poker_test_graph
    ├── poker_test_summary
    ├── rsa_decrypt
    ├── rsa_encrypt
    ├── rsa_keygen
    ├── vigenere_analysis_window
    ├── vigenere_ciphertext
    ├── vigenere_decrypt
    ├── vigenere_encrypt_window
    └── vigenere_key_found

1. Caesar Cipher
1.1 Encryption (Key = 3)

Plaintext:
THIS IS MY CRYPTOGRAPHY LAB

The Caesar cipher shifts each letter by 3 positions.

Screenshots:

caesar_encrypt_window

caesar_ciphertext

1.2 Decryption

Applied the same key (3) to recover the original plaintext.

Screenshot:

caesar_decrypt

1.3 Brute-Force Analysis

CrypTool computed all 25 possible shifts and presented every candidate plaintext.

Screenshot:

caesar_bruteforce

2. Vigenère Cipher
2.1 Encryption (Key = SECURITY)

Plaintext:
CRYPTOGRAPHY PROJECT USING VIGENERE

Key: SECURITY
A polyalphabetic method that uses repeating key letters.

Screenshots:

vigenere_encrypt_window

vigenere_ciphertext

2.2 Decryption

Used the same key (SECURITY) to retrieve the original message.

Screenshot:

vigenere_decrypt

2.3 Vigenère Analysis (Key Discovery)

CrypTool performed:

Key length estimation

Autocorrelation analysis

Pattern matching

Statistical scoring

It successfully identified the structure of the encryption.

Screenshots:

vigenere_analysis_window

vigenere_key_found

3. RSA Public-Key Cryptography
3.1 Key Generation (1024-bit)

Generated a 1024-bit RSA keypair inside CrypTool.

Screenshot:

rsa_keygen

3.2 RSA Encryption

Plaintext:
HELLO RSA

Using the generated public key, CrypTool produced RSA ciphertext.

Screenshot:

rsa_encrypt

3.3 RSA Decryption

Recovered the plaintext using the private key.

Screenshot:

rsa_decrypt

4. Poker Test – Randomness Evaluation

The Poker Test was performed on the Vigenère ciphertext to evaluate randomness.
Classical ciphers always fail randomness tests, which is expected.

4.1 Graph Output

Displays distribution used in randomness scoring.

Screenshot:

poker_test_graph

4.2 Summary / Score

CrypTool reported:

Expected (maximal) test value

Actual computed score

Result: Poker test failed → normal for classical ciphers

Screenshot:

poker_test_summary

Key Learning Outcomes

Through this lab, I practiced:

Classical encryption (Caesar, Vigenère)

Public-key cryptography (RSA)

Cryptanalysis methods

Randomness testing

Documentation and portfolio structuring skills

This project serves as evidence of hands-on cryptography knowledge suitable for:

Cybersecurity Analyst roles

SOC Analyst positions

Threat Intelligence

Academic cryptography foundations
