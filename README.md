# Cryptography Lab – Caesar, Vigenère, RSA & Poker Test
Hands-on cryptography using CrypTool 1.4.42. 
This project covers classical ciphers, RSA, and randomness testing with screenshots documenting each step.

## Project Overview
This lab demonstrates:

- Caesar cipher encryption & decryption  
- Vigenère cipher encryption & key analysis  
- RSA 1024-bit keypair generation, encryption & decryption  
- Poker Test randomness evaluation  

The goal was to understand how different cryptographic algorithms behave and how cryptanalysis helps reveal patterns.

---

# 1. Caesar Cipher

## 1.1 Encryption (Key = 3)
- Typed plaintext: `THIS IS MY CRYPTOGRAPHY LAB`
- Applied a Caesar shift of 3.

**Screenshots:**  
- `caesar_encrypt_window`  
- `caesar_ciphertext`

---

## 1.2 Decryption
- Used the same key (3) to recover original plaintext.

**Screenshot:**  
- `caesar_decrypt`

---

## 1.3 Brute-Force Attack
- Selected ciphertext and ran Caesar Analysis in CrypTool.
- Tool displayed all 25 possible shifts.

**Screenshot:**  
- `caesar_bruteforce`

---

# 2. Vigenère Cipher

## 2.1 Encryption (Key = SECURITY)
- Typed plaintext: `CRYPTOGRAPHY PROJECT USING VIGENERE`
- Used key: SECURITY
- CrypTool generated ciphertext.

**Screenshots:**  
- `vigenere_encrypt_window`  
- `vigenere_ciphertext`

---

## 2.2 Decryption
- Decrypted with same key.

**Screenshot:**  
- `vigenere_decrypt`

---

## 2.3 Vigenère Key Analysis
- Ran Vigenère Analysis on ciphertext.
- CrypTool estimated key length and patterns.

**Screenshots:**  
- `vigenere_analysis_window`  
- `vigenere_key_found`

---

# 3. RSA – Public Key Cryptography

## 3.1 RSA Key Generation (1024-bit)
- Generated RSA public/private keypair using CrypTool.

**Screenshot:**  
- `rsa_keygen`

---

## 3.2 RSA Encryption
- Encrypted plaintext: `HELLO RSA`
- Produced RSA ciphertext blocks.

**Screenshot:**  
- `rsa_encrypt`

---

## 3.3 RSA Decryption
- Highlighted ciphertext → RSA Decrypt
- CrypTool recovered original plaintext.

**Screenshot:**  
- `rsa_decrypt`

---

# 4. Poker Test (Randomness Evaluation)

## 4.1 Graph Output
- Ran Poker Test on Vigenère ciphertext.
- Viewed statistical distribution.

**Screenshot:**  
- `poker_test_graph`

---

## 4.2 Summary / Score
- CrypTool reported expected vs. actual score.
- Result: **Poker Test Failed** (normal for classical ciphers)

**Screenshot:**  
- `poker_test_summary`

---

# Skills Demonstrated
- Classical encryption (Caesar, Vigenère)
- Modern public-key cryptography (RSA)
- Cryptanalysis and key estimation
- Randomness analysis
- Lab documentation with screenshots

# Conclusion
This project provided hands-on experience with encryption, decryption, cryptanalysis, and randomness evaluation, demonstrating essential skills for cybersecurity and SOC analysis roles.

## Author  
**Umme Farva**  
Cybersecurity Analyst
