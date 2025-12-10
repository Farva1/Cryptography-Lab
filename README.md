Cryptography Lab (Caesar, Vigenère, RSA & Poker Test)

Author: Umme Farva
Tools Used: CrypTool 1.4.42

Overview

This project demonstrates several foundational cryptographic techniques using CrypTool, including:

Caesar Cipher – classical substitution cipher

Vigenère Cipher – polyalphabetic encryption

RSA – modern public-key cryptography (1024-bit keypair)

Poker Test – randomness evaluation of ciphertext

The goal is to understand how classical and modern cryptography work, how they can be analyzed, and how attackers perform cryptanalysis.

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

Applied a shift of 3 positions.

Screenshots:

caesar_encrypt_window

caesar_ciphertext

1.2 Decryption

Recovered original plaintext using the same key.

Screenshot:

caesar_decrypt

1.3 Brute-Force Attack

CrypTool tests all 25 possible Caesar shifts and displays each result.

Screenshot:

caesar_bruteforce

2. Vigenère Cipher
2.1 Encryption (Key = SECURITY)

Plaintext:
CRYPTOGRAPHY PROJECT USING VIGENERE

CrypTool applies polyalphabetic substitution.

Screenshots:

vigenere_encrypt_window

vigenere_ciphertext

2.2 Decryption

Recovered plaintext using the same key.

Screenshot:

vigenere_decrypt

2.3 Vigenère Analysis / Key Discovery

CrypTool performed statistical analysis to detect:

Key length

Repeating patterns

Correlation spikes

Actual key guess

Screenshots:

vigenere_analysis_window

vigenere_key_found

3. RSA Public-Key Cryptography
3.1 Key Generation (1024-bit)

Generated a public/private key pair inside CrypTool.

Screenshot:

rsa_keygen

3.2 RSA Encryption

Encrypted the plaintext:

HELLO RSA

Screenshot:

rsa_encrypt

3.3 RSA Decryption

Recovered the original plaintext using the private key.

Screenshot:

rsa_decrypt

4. Poker Test – Randomness Evaluation

The Poker Test was executed on Vigenère ciphertext to measure randomness quality.

4.1 Graph Output

Shows the statistical distribution and randomness behavior.

Screenshot:

poker_test_graph

4.2 Summary / Score

CrypTool displays:

Expected test value

Actual test score

Result: failed (expected — Vigenère is not random)

Screenshot:

poker_test_summary

Key Learning Outcomes

Through this lab, I practiced and demonstrated:

Classical encryption (Caesar, Vigenère)

Modern public-key cryptography (RSA)

Cryptanalysis & statistical attacks

Randomness testing using Poker Test

Proper lab documentation for cybersecurity portfolios

Author

Umme Farva
Cybersecurity Analyst | SOC & Cryptography Learner
