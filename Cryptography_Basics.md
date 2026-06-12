# Cryptography Notes

## Introduction to Cryptography

Cryptography is the practice of securing information by converting readable data into an unreadable format to protect it from unauthorized access.

## Objectives of Cryptography

* Confidentiality
* Integrity
* Authentication
* Non-Repudiation

## Symmetric Encryption

In symmetric encryption, the same key is used for both encryption and decryption.

### Advantages

* Fast
* Efficient for large amounts of data

### Example Algorithms

* AES
* DES

## Asymmetric Encryption

In asymmetric encryption, two keys are used:

* Public Key
* Private Key

### Advantages

* More secure for communication
* Supports digital signatures

### Example Algorithms

* RSA
* ECC

## Hashing

Hashing converts data into a fixed-length value called a hash.

### Characteristics

* One-way process
* Cannot be reversed
* Used for integrity verification

### Common Hashing Algorithms

* MD5
* SHA-1
* SHA-256

### Example

Input:

```text
hello
```

SHA-256 Output:

```text
2cf24dba5fb0a...
```

## Digital Certificates

Digital certificates verify the identity of websites and users. They are issued by trusted Certificate Authorities (CAs).

## SSL/TLS

SSL/TLS protocols provide secure communication over the internet by encrypting data exchanged between clients and servers.

### Uses

* Secure websites (HTTPS)
* Online banking
* Secure email communication

## OpenSSL

OpenSSL is an open-source tool used for:

* Encryption
* Decryption
* Certificate management
* Secure communication testing

## Conclusion

Cryptography protects sensitive information from unauthorized access and ensures secure communication over networks. It is an essential component of modern cybersecurity.

---

These notes are enough for **Task 1 documentation** and should be about **3–4 pages combined** when added to your report with screenshots. 
