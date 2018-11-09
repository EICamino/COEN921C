# Week 4 - Cryptography


## Summarize

Cryptography: making and using codes to secure information.

Cryptoanalysis: decryption without knowing the keys.

Cryptology: Cryptography + Cryptoanalysis

1. Terms:
    - Algorithm: steps to convert unencrypted message to encrypted sequence, also refer to programs doing this.
    - Cipher/Cryptosystem: encryption method, encompassing algorithms, keys and procedures to perform encryption and decryption.
    - Ciphertext/Cryptogram: encoded message after encryption
    - Plaintext/cleartext: unencrypted/depcrypted message.
    - Decipher: decrypt, decode or convert to ciphertext to planintext
    - Encipher: encrypt, encode or convert to planintext to ciphertext
    - Key/cryptovariable: info conjunct with an algorithm to encrypt/decrypt
    - Keyspace: entire range of values that can be used to construct key.

1. Category:
    - bit
        - XOR
    - block
        - substitution
            - Mono-alphabetic
            - Poly-alphabetic
            - Vigenere: symmetric
        - transposition
            - rearranging binaries within a block by given
            - Vernam
            - Book-based cipher: dict, including all words
        - XOR
            - simple implementation simple break
        - combination

1. Hash
    - Convert variable-length message to fixed length value.
    - One way
    - Store passwords


## Quiz


### Quiz 1

> What is cryptography and cryptanalysis?

Encryption, decryption without knowing the keys.


### Quiz 2

> What was the earliest reason for the use of cryptography?

Concealing military and political secrets while they were transported from place to place.


### Quiz 3

> What is a cryptographic key, and what is it used for? What is a more formal name for a cryptographic key?

1. Cryptographic key is the information used in conjunction with an algorithm to create the ciphertext from the plaintext or derive the1. aintext from the ciphertext. The key can be a series of bits used by a computer program, or it can be a passphrase used by people that1.  then converted into a series of bits for use in the computer program.
1. Also known as a crypto variable.


### Quiz 4

> What are the three basic operations in cryptography?

Encrypting, decrypting, and hashing


### Quiz 5

> What is a hash function, and what can it be used for?

1. Mathematical algorithms that generate a message summary or digest to confirm the identity and integrity.
1. Convert variable-length messages into a single fixed-length value, and different messages have different digests.


### Quiz 6

> What does it mean to be “out of band”? Why is it important to exchange keys out of band in symmetric encryption?

1. Avoid interception
1. Use a band other than the one carrying the ciphertext.


### Quiz 7

> What is the fundamental difference between symmetric and asymmetric encryption?

- | Symmetric | Asymmetric
--- | --- | ---
Also known as             | private key encryption          | public key encryption
Types of keys             | 1, private                      | 2, public and private
Encryption and decryption | Same key                        | Different key
Problem                   | Send the key to the receiver    | Slower


### Quiz 8

> How does public key infrastructure add value to an organization seeking to use cryptography to protect information assets?

PKI makes the use of cryptographic systems more convenient and cost-effective.


### Quiz 9

> What are the components of PKI?

RA (Regulation Authority), CA (Certificate Authority), CD (Certificate directories), Protocols, Policies and Procedures. 


### Quiz 10

> What is the difference between a digital signature and a digital certificate?

1. Digital signatures are encrypted messages that can be verified with the help of hashing
1. Digital certificates are files that contain public key that are used to identify the ownership of computer applications. 


### Quiz 11

> What critical issue in symmetric and asymmetric encryption is resolved by using a hybrid method like Diffie-Hellman?

3rd party transfer compromising.


### Quiz 12

> What is steganography, and what can it be used for?

1. Hiding messages by secret writing.
1. Protect confidential info.


### Quiz 13

> Which security protocols are predominantly used in Web-based e-commerce?

Abbr. | Full name
--- | ---
SSL    | secure sockets layer
S-HTTP | secure hypertext transfer protocol
SET    | secure electronic transactions


### Quiz 14

> Which security protocols are used to protect e-mail?

Abbr. | Full name
--- | ---
S/MIME | secure multipurpose internet mail extensions
PEM    | privacy enhanced mail
PGP    | pretty good privacy


### Quiz 15

> IPSec can be implemented using two modes of operation. What are they?

Transport and tunnel


### Quiz 16

> Which kind of attack on cryptosystems involves using a collection of pre-identified terms? Which kind of attack involves sequential guessing of all possible key combinations?

1. Dictionary attack, rainbow cracking
1. Brute force attack


### Quiz 17

> If you were setting up an encryption-based network, what key size would you choose and why?

1. Choose the largest key size consistent with the tools being used and the overhead performance burden it would impose on the environment.
1. The current "gold standard" is to ensure that all computing devices are capable of AES 256-bit encryption.


### Quiz 18

> What is the typical key size of a strong encryption system used on the Web today?

At least 256 bits


### Quiz 19

> What encryption standard is currently recommended by NIST?

AES (advanced encryption standard)


### Quiz 20

> What are the most popular encryption systems used over the Web?

Abbr. | Full name
--- | ---
symmetric   | AES
asymmetric  | RSA
hybrid      | PGP