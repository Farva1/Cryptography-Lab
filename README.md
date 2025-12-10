Cryptography Lab – Caesar, Vigenère, RSA & Poker Test

Author: Umme Farva
Tools Used: CrypTool 1.4.42

Overview

This project demonstrates several foundational cryptographic techniques using CrypTool, including:

Caesar Cipher – classical substitution cipher

Vigenère Cipher – polyalphabetic encryption

RSA – public-key cryptography (1024-bit keypair generation)

Poker Test – randomness analysis of ciphertext

The goal of this lab is to understand how classical and modern cryptography work, how they fail, and how attackers analyze ciphertext.

All screenshots and supporting files are included for documentation and portfolio evidence.

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

Plaintext: THIS IS MY CRYPTOGRAPHY LAB

Shift: 3 positions forward

Screenshots

caesar_encrypt_window – configuration

caesar_ciphertext – encrypted output

1.2 Decryption

Used the same key (3) to recover the original plaintext.

Screenshot

caesar_decrypt

1.3 Brute-Force Attack

CrypTool analyzes all 25 possible shifts and displays every result.

Screenshot

caesar_bruteforce

2. Vigenère Cipher
2.1 Encryption (Key = SECURITY)

Plaintext: CRYPTOGRAPHY PROJECT USING VIGENERE

Key: SECURITY

Screenshots

vigenere_encrypt_window

vigenere_ciphertext

2.2 Decryption

Recovered the plaintext using the same key.

Screenshot

vigenere_decrypt

2.3 Vigenère Analysis (Key Discovery)

CrypTool performed statistical analysis to estimate:

key length

repeating patterns

correlation peaks

It successfully identified the key characteristics.

Screenshots

vigenere_analysis_window

vigenere_key_found

3. RSA Public-Key Cryptography
3.1 Key Generation

Generated a 1024-bit RSA keypair inside CrypTool.

Screenshot

rsa_keygen

3.2 RSA Encryption

Encrypted plaintext:

HELLO RSA


Screenshot

rsa_encrypt

3.3 RSA Decryption

Decrypted the ciphertext back to readable form.

Screenshot

rsa_decrypt

4. Poker Test – Randomness Evaluation

The Poker Test was performed on the Vigenère ciphertext to measure randomness behavior.

4.1 Graph Output

Shows the statistical distribution used in randomness testing.

Screenshot

poker_test_graph

4.2 Summary / Score

CrypTool reports:

maximal expected score

actual score

Result: failed (normal for classical ciphers)

Screenshot

poker_test_summary

Key Learning Outcomes

Through this lab, I practiced:

Classical encryption methods (Caesar, Vigenère)

Modern public-key cryptography (RSA)

Cryptanalysis concepts

Randomness evaluation using statistical tests

Documenting technical processes with evidence

This project is designed to showcase foundational cryptography skills relevant to cybersecurity, SOC analysis, and threat intelligence.
