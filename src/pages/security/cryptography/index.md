---
title: Cryptography
---

## Cryptography

The basic objective of cryptography is to enable two people to communicate through the unsecure channel in such a way that a third person cannot understand what is being said. This channel could be a telephone line or a computer network. 

Cryptography started being used by the Romans in order to make messages in battle unreadable by the enemy if decyphered. 

Cryptography prior to the modern age was effectively synonymous with encryption, the conversion of information from a readable state to apparent nonsense. 

Modern cryptography is used in data so that only one party or only authorised partys have the ability to access the information. 

Encryption over the years has become more advanced.

### Example

The information that Person1 wants to send to Person2, which we call "plaintext", can be text, numerical data, or any type of data at all. Person1 encrypts the plaintext, using a predetermined key, and sends the resulting "ciphertext" over the channel. Person3, upon seeing the ciphertext in the channel, cannot determine what the plaintext was, but Person2, who knows the encryption key, can decrypt the ciphertext and reconstruct the plaintext.

### Caesar Cypher (Shift Cypher)

The first known cypher was the Ceasar cypher. The Ceasar cypher works by shifting the letters of a "plaintext" by a specific amount up or down in the alphabet. 

From an outside person's perspective, the message appears to be random letters with spaces in between.

### Modern Cryptography

Modern encryption uses almost random numbers and mathematically sound functions in order to allow secure communication. These newly developed functyions cannot be easily cracked due to their structure, requiring even supercomputers hundreds of years to crack.

There are 2 main types of modern encryption:

### 1) Symmetric or Single Key Encryption:

Symmetric Key Encryption is an encryption method where both parties use only one key for encryption and decryption. These algorithms, due to their design, are generally much faster than Asymmetric or Public Key Encryption.

Some Symmetric encryption techniques include: Data Encryption Standard (DES), Advance Encryption Standard (AES), Blow Fish, Two Fish, RC4.

### 2) Asymmetric or Public Key Encryption:

Asymmetric Encryption algorithms provide each user with a pair of keys: one public and one private. Any message encrypted with one key from the pair can only be decrypted with the other. 

Some Asymmetric techniques include: RSA, Diffie-Hellman, DSS(Digital Signature Standard), ElGamal.

### Cryptography Application

Cryptography is used in the CTF(capture the flag) competitions where hackers from all over the world participate to hack their way out to get a flag from a file. Cryptography is a major type in CTF where many different types of ciphers like Caesar, Atbash, Affine, Playfair, hashes are used. To get a taste on cryptography in CTF you can visit https://picoctf.com/ it have all sort of questions starting from begineers to advanced.

### Cryptographic Hashing

Most cryptographic hash functions are designed to take a string of any length as input and produce a fixed-length hash value.

A cryptographic hash function must be able to withstand all known types of cryptanalytic attack.

### Cryptography Hashing
A cryptographic hash function is a type of hash function that is designed to also be a one-way function (a function that takes too much time and resources to brute force). The main purpose of hashes deal with message intregrity, so the same message always results in the same hash.

### Cryptography and it's scope in CTF
Cryptography is a world famous section in CTF(capture the flag) competitions where hackers from all over the world take part in it and hack their way to retrieve a key from a given file. The goal is usually to crack or clone cryptographic objects or algorithms to reach the flag. Cryptography in the past years have been evolved adding on to caeser cipher, to various forms like 'Atbash', 'Affine', 'Baconian', 'Transportation' and many more. 

You can practice your Cryptography skills on https://picoctf.com/ (a CTF competition) where you can find questions ranging from begineer to advanced level.

#### More Information:

- [Cryptography: Theory and Practice by Douglas Stinson](https://www.crcpress.com/Cryptography-Theory-and-Practice-Third-Edition/Stinson/p/book/9781584885085)
- [TechTarget on Encryption](http://searchsecurity.techtarget.com/definition/encryption)
- [Cryptography Guide](https://www.tutorialspoint.com/cryptography/index.htm)
