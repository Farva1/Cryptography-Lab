# Cryptography Lab (Caesar, Vigenère, RSA & Poker Test)

**Author:** Umme Farva  
**Tools Used:** CrypTool 1.4.42  

---

## Overview

This project demonstrates several foundational cryptographic techniques using CrypTool, including:

- **Caesar Cipher** – classical substitution cipher  
- **Vigenère Cipher** – polyalphabetic encryption  
- **RSA** – public-key cryptography (1024-bit keypair generation)  
- **Poker Test** – randomness evaluation of ciphertext  

The goal is to understand how classical and modern cryptography work, how they fail, and how attackers perform cryptanalysis.

All screenshots are included for documentation and portfolio evidence.

---

## Project Structure

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

---

# 1. Caesar Cipher

## 1.1 Encryption (Key = 3)

**Plaintext:**  
`THIS IS MY CRYPTOGRAPHY LAB`

Applied a shift of **3**.

**Screenshots:**  
- caesar_encrypt_window  
- caesar_ciphertext  

---

## 1.2 Decryption

Recovered original plaintext using key **3**.

**Screenshot:**  
- caesar_decrypt  

---

## 1.3 Brute-Force Analysis

CrypTool tests all 25 Caesar shifts.

**Screenshot:**  
- caesar_bruteforce  

---

# 2. Vigenère Cipher

## 2.1 Encryption (Key = SECURITY)

**Plaintext:**  
`CRYPTOGRAPHY PROJECT USING VIGENERE`

**Screenshots:**  
- vigenere_encrypt_window  
- vigenere_ciphertext  

---

## 2.2 Decryption

Recovered plaintext using the same key.

**Screenshot:**  
- vigenere_decrypt  

---

## 2.3 Vigenère Key Analysis

CrypTool identifies:

- Key length  
- Repeated sequences  
- Correlation spikes  

**Screenshots:**  
- vigenere_analysis_window  
- vigenere_key_found  

---

# 3. RSA Public-Key Cryptography

## 3.1 Key Generation (1024-bit)

Generated RSA public/private key pair.

**Screenshot:**  
- rsa_keygen  

---

## 3.2 RSA Encryption

**Message:** `HELLO RSA`

**Screenshot:**  
- rsa_encrypt  

---

## 3.3 RSA Decryption

Original plaintext recovered.

**Screenshot:**  
- rsa_decrypt  

---

# 4. Poker Test (Randomness Evaluation)

## 4.1 Graph Output

Statistical distribution of ciphertext.

**Screenshot:**  
- poker_test_graph  

---

## 4.2 Summary

Shows:

- Expected score  
- Actual score  
- Result: **Failed** (normal for classical ciphers)

**Screenshot:**  
- poker_test_summary  

---

# Key Learning Outcomes

- Learned classical and modern encryption  
- Practiced cryptanalysis techniques  
- Evaluated randomness with Poker Test  
- Documented full cybersecurity lab with screenshots  

---

# Author

**Umme Farva**  
Cybersecurity Analyst & SOC Learner
