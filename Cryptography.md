# Cryptography

Cryptography is the science and practice of securing communication and data from unauthorized access or alteration. It encompasses various techniques designed to protect information by transforming it into a secure format that can only be converted back to its original form by someone with the correct decryption key.

## Main Aspects of Cryptography

### Encryption and Decryption

- **Encryption**: The process of converting plain text (readable data) into ciphertext (unreadable data) using an algorithm and an encryption key.
- **Decryption**: The process of converting ciphertext back into plain text using a decryption key.

### Keys

- **Symmetric Key Cryptography**: Uses the same key for both encryption and decryption. It's efficient but requires secure key distribution.
- **Asymmetric Key Cryptography**: Uses a pair of keys (public key and private key). The public key encrypts the data, and the private key decrypts it, facilitating secure key exchange.

### Algorithms

Cryptographic algorithms are mathematical procedures used for encryption and decryption. Common algorithms include:

- **AES (Advanced Encryption Standard)**
- **RSA (Rivest-Shamir-Adleman)**
- **ECC (Elliptic Curve Cryptography)**

### Hash Functions

Hash functions take an input (or 'message') and return a fixed-size string of bytes. They are designed to be a one-way function, meaning it should be infeasible to invert the function and retrieve the original input. Common hash functions include:

- **SHA-256 (Secure Hash Algorithm 256-bit)**
- **MD5 (Message Digest Algorithm 5)**

### Digital Signatures

Digital signatures are a way to verify the authenticity and integrity of a message, software, or digital document. They are often used in conjunction with asymmetric cryptography.

### Cryptographic Protocols

- **SSL (Secure Sockets Layer)** and its successor, **TLS (Transport Layer Security)**, are cryptographic protocols that provide secure communication over a computer network. They use a combination of symmetric and asymmetric encryption to protect data transmitted over the internet.
- **HTTPS**: The secure version of HTTP, uses SSL/TLS to encrypt data between the web browser and the server.

## Applications of Cryptography

- **Confidentiality**: Ensuring that information is not accessed by unauthorized individuals.
- **Integrity**: Protecting information from being altered by unauthorized parties.
- **Authentication**: Verifying the identity of individuals or entities.
- **Non-repudiation**: Ensuring that a party cannot deny the authenticity of their signature on a document or a message that they sent.

Cryptography is essential in many aspects of modern life, including secure communication, online banking, digital currencies (such as Bitcoin), and securing sensitive information in both personal and professional contexts. Understanding these key concepts is crucial for implementing effective security measures in any digital system.

[Back](MS.md) / [Next Page](Q.md)
