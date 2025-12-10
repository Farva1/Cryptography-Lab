Cryptography Lab – Caesar, Vigenère, RSA, Poker Test

This project demonstrates classical and modern cryptography techniques using CrypTool 1.4.42.
It includes Caesar Cipher, Vigenère Cipher, RSA public-key encryption, and a randomness Poker Test.
All screenshots are stored inside the screenshots folder.

📁 Project Structure
Cryptography-Lab/
│
├── README.md
└── screenshots/
    ├── caesar_encrypt_window
    ├── caesar_ciphertext
    ├── caesar_decrypt
    ├── caesar_bruteforce
    ├── vigenere_encrypt_window
    ├── vigenere_ciphertext
    ├── vigenere_decrypt
    ├── vigenere_analysis_window
    ├── vigenere_key_found
    ├── rsa_keygen
    ├── rsa_encrypt
    ├── rsa_decrypt
    ├── poker_test_graph
    └── poker_test_summary

1️⃣ Caesar Cipher
🔸 Encryption (Key = 3)

Plaintext: THIS IS MY CRYPTOGRAPHY LAB
Applied Caesar shift of 3.

📸 Screenshot: caesar_encrypt_window
📸 Screenshot: caesar_ciphertext

🔸 Decryption

Used the same key to restore original plaintext.

📸 Screenshot: caesar_decrypt

🔸 Brute-Force Attack

CrypTool attempted all 25 possible shifts and showed all results.

📸 Screenshot: caesar_bruteforce

2️⃣ Vigenère Cipher
🔸 Encryption (Key = SECURITY)

Encrypted plaintext using Vigenère algorithm.

📸 Screenshot: vigenere_encrypt_window
📸 Screenshot: vigenere_ciphertext

🔸 Decryption

Recovered plaintext using same key.

📸 Screenshot: vigenere_decrypt

🔸 Vigenère Analysis / Key Discovery

CrypTool analyzed:

Key length

Possible key characters

Correlation patterns

📸 Screenshot: vigenere_analysis_window
📸 Screenshot: vigenere_key_found

3️⃣ RSA Public-Key Cryptography
🔸 Key Generation (1024-bit)

Generated RSA public/private key pair.

📸 Screenshot: rsa_keygen

🔸 RSA Encryption

Encrypted: HELLO RSA

📸 Screenshot: rsa_encrypt

🔸 RSA Decryption

Decrypted ciphertext back to plaintext.

📸 Screenshot: rsa_decrypt

4️⃣ Poker Test – Randomness Analysis

Ran Poker Test on Vigenère ciphertext.
Result: failed (expected — Vigenère is not secure and not random).

📸 Screenshot: poker_test_graph
📸 Screenshot: poker_test_summary

✅ Summary

This lab demonstrates:

Caesar Cipher (encryption, decryption, brute force)

Vigenère Cipher (encryption, decryption, key estimation)

RSA (key generation, encryption & decryption)

Randomness evaluation with Poker Test

Proper documentation and screenshots for a cybersecurity portfolio
