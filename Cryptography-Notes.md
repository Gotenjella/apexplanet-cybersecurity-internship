# Cryptography Notes

## 1. Introduction

Cryptography is used to protect information through encryption, hashing, digital certificates, and secure communication protocols.

## 2. Symmetric Encryption

Symmetric encryption uses the same secret key for encryption and decryption.

### Advantages
- Fast and efficient
- Suitable for encrypting large amounts of data

### Limitation
The secret key must be securely shared between communicating parties.

## 3. Asymmetric Encryption

Asymmetric cryptography uses a pair of keys:

- Public Key
- Private Key

The public key can be shared, while the private key must be kept secret.

### Common Uses
- Secure communication
- Digital signatures
- Key exchange
- Digital certificates

## 4. Hashing

Hashing converts input data into a fixed-length output called a hash value.

Hashing is commonly used for:
- Data integrity verification
- File integrity monitoring
- Password protection
- File comparison

Hashing is designed to be a one-way process.

## 5. MD5

MD5 is a cryptographic hash function that produces a 128-bit hash.

MD5 is considered unsuitable for modern security-sensitive applications because practical collision attacks exist.

## 6. SHA-256

SHA-256 is a member of the SHA-2 family of cryptographic hash functions.

It produces a 256-bit hash value.

### Common Uses
- File integrity verification
- Digital signatures and security systems
- Data verification
- Checksums

### Example

```bash
echo -n "Hello Cybersecurity" | sha256sum
