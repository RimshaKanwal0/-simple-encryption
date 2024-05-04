# simple-encryption
# Simple Encryption and Decryption Program

This is a simple encryption and decryption program written in Python. It uses a **basic substitution cipher** technique to encrypt and decrypt text.

## Encryption
Encryption turns readable data (plaintext) into unreadable data (ciphertext) using an algorithm and a key, ensuring data confidentiality and security.

## Decryption
Decryption reverses this process, converting ciphertext back into plaintext using the appropriate key and algorithm.

## Substitution Cipher
The encryption technique used in the provided code is a simple form of Substitution Cipher:

- In the `encryption` function, each character of the plaintext is substituted with a character whose ASCII value is increased by the length of the password.
- In the `decryption` function, the opposite process occurs, where each character of the encrypted text is substituted back to its original value by subtracting the length of the password.


## Types of Encryption:

1) Symmetric Encryption:
Uses the same key for both encryption and decryption.
Examples: DES, AES, 3DES.
2) Asymmetric Encryption:
Uses a pair of keys - public key for encryption and private key for decryption.
Public key is freely available, private key is kept secret.
Examples: RSA, DSA, ECC.
## Output
![Screenshot (7)](https://github.com/RimshaKanwal0/-simple-encryption/assets/164622299/f52b53f6-5608-4482-859a-edfbb9ab990c)



