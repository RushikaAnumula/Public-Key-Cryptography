# Public Key Cryptography (PKI)
Public Key Cryptography, also known as Public Key Infrastructure (PKI), is a security framework used to enable secure and authenticated communication over public networks such as the internet.
PKI uses asymmetric cryptography, where a pair of keys (public key and private key) is used to protect data, verify identities, and ensure data integrity.

## What is Cryptography?
Cryptography is the practice of securing information by converting it into an unreadable format so that only authorized parties can access it.

## Public Key Infrastructure (PKI)
PKI is a comprehensive framework that consists of hardware, software, policies, and procedures used to manage digital certificates and public-key encryption.
It ensures:
- Confidentiality
- Authentication
- Data Integrity

## Core Concepts
### Asymmetric Cryptography
- Uses a public key and a private key
- Data encrypted using a public key can only be decrypted using the corresponding private key

### Digital Certificates
- Act as digital identity proofs (X.509 standard)
- Bind public keys to users, devices, or applications

### Certificate Authority (CA)
- Trusted third party responsible for issuing and managing digital certificates

### Registration Authority (RA)
- Verifies identities before certificates are issued by the CA

### Key Management
- Handles key generation, storage, distribution, and revocation

## Benefits of PKI
- Secure communication over public networks
- Strong authentication of users and devices
- Protection against Man-in-the-Middle (MITM) attacks
- Scalable and suitable for large organizations
- Supports regulatory compliance (e.g., GDPR)

## Limitations of PKI
- Complex infrastructure to manage
- Heavy reliance on trusted Certificate Authorities
- Security risks if private keys are compromised

## Applications of PKI
- Secure web communication (HTTPS / SSL)
- Digital signatures
- Online banking and e-commerce
- Secure email communication
- Authentication systems (VPNs, cloud services)
