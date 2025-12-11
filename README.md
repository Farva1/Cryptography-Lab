# Cryptography Lab – Caesar, Vigenère, RSA & Poker Test

**Author:** Umme Farva  
**Tool Used:** CrypTool 1.4.42

This project demonstrates foundational cryptographic techniques including classical ciphers (Caesar, Vigenère), modern RSA encryption, and randomness testing using the Poker Test.  
All steps include screenshots stored in the **Screenshots/** folder.

---

## Project Structure

Cryptography-Lab/
│── README.md
└── Screenshots/
├── caesar_bruteforce.png
├── caesar_ciphertext.png
├── caesar_decrypt.png
├── caesar_encrypt_window.PNG
├── poker_test_graph.png
├── poker_test_summary.PNG
├── rsa_decrypt.png
├── rsa_encrypt.png
├── rsa_keygen.PNG
├── vigenere_analysis_window.PNG
├── vigenere_ciphertext.png
├── vigenere_decrypt.png
├── vigenere_encrypt_window.PNG
├── vigenere_key_found.png

yaml
Copy code

---

# 1. Caesar Cipher

## **1.1 Encryption (Key = 3)**

Plaintext:  
THIS IS MY CRYPTOGRAPHY LAB

yaml
Copy code

**Encryption Window:**  
![Caesar Encrypt](Screenshots/caesar_encrypt_window.PNG)

**Ciphertext Output:**  
![Caesar Ciphertext](Screenshots/caesar_ciphertext.png)

---

## **1.2 Decryption**
Recovered original plaintext.

![Caesar Decrypt](Screenshots/caesar_decrypt.png)

---

## **1.3 Brute-Force Attack**
CrypTool tested all 25 shifts.

![Caesar Bruteforce](Screenshots/caesar_bruteforce.png)

---

# 2. Vigenère Cipher

## **2.1 Encryption (Key = SECURITY)**

Plaintext:  
CRYPTOGRAPHY PROJECT USING VIGENERE

yaml
Copy code

**Vigenère Encryption Window:**  
![Vigenere Encrypt Window](Screenshots/vigenere_encrypt_window.PNG)

**Ciphertext Output:**  
![Vigenere Ciphertext](Screenshots/vigenere_ciphertext.png)

---

## **2.2 Decryption**

![Vigenere Decrypt](Screenshots/vigenere_decrypt.png)

---

## **2.3 Vigenère Key Analysis**

CrypTool identifies:

- possible key length  
- repeating patterns  
- correlation peaks  

**Analysis Window:**  
![Vigenere Analysis](Screenshots/vigenere_analysis_window.PNG)

**Key Found:**  
![Vigenere Key Found](Screenshots/vigenere_key_found.png)

---

# 3. RSA Public-Key Cryptography

## **3.1 RSA Key Generation (1024-bit)**

![RSA Keygen](Screenshots/rsa_keygen.PNG)

---

## **3.2 RSA Encryption**

Plaintext:  
HELLO RSA

yaml
Copy code

![RSA Encrypt](Screenshots/rsa_encrypt.png)

---

## **3.3 RSA Decryption**

![RSA Decrypt](Screenshots/rsa_decrypt.png)

---

# 4. Poker Test – Randomness Evaluation

Performed on Vigenère ciphertext.

**Graph Output:**  
![Poker Graph](Screenshots/poker_test_graph.png)

**Summary (Score):**  
![Poker Summary](Screenshots/poker_test_summary.PNG)

Result: **FAILED** — expected because classical ciphers are not random.

---

# Skills Demonstrated

- Classical encryption (Caesar, Vigenère)
- Modern RSA public/private key operations
- Cryptanalysis techniques
- Statistical randomness testing
- Documentation & screenshot-based reporting

---

# Summary

This cryptography lab provides hands-on experience with both classical and modern cryptographic methods using CrypTool. It is structured for use in cybersecurity portfolios and academic submissions.

---
