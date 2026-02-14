# 🔐 Public-Key Cryptography (PKI)
Public Key Infrastructure (PKI) is a comprehensive security framework that includes **hardware, software, policies, and procedures**.  
It is designed to manage **digital certificates** and **public-key encryption**, ensuring secure and authenticated communication over public networks.
PKI uses a pair of cryptographic keys:
- **Public Key**
- **Private Key**
These keys help **verify identities** and **protect data integrity**.  
Key components of PKI include **Certification Authorities (CAs)**, **Registration Authorities (RAs)**, and **certificate repositories**.

## ⚙️ Core Components and Functions
### 🔑 Asymmetric Cryptography
- Uses a **key pair** (public and private)
- Data encrypted with a public key can only be decrypted using the corresponding private key
### 🪪 Digital Certificates
- Act as a **digital passport**
- Follow the **X.509 standard**
- Bind a public key to a user, device, or application
### 🏛️ Certificate Authority (CA)
- Trusted third party
- Issues, signs, and manages digital certificates
### 🧾 Registration Authority (RA)
- Verifies user identities
- Approves certificate requests before CA issuance
### 🔄 Key Management
- Manages the entire key lifecycle
- Includes key generation, storage, distribution, and revocation

## ✅ Key Benefits of PKI
- **Enhanced Security**
  - Protects sensitive data
  - Prevents Man-in-the-Middle (MITM) attacks
  - Ensures confidentiality and authenticity
- **Authentication**
  - Verifies users and devices before granting access
- **Scalability & Compliance**
  - Supports large organizations
  - Helps meet regulatory requirements such as **GDPR**

## ⚠️ Limitations of PKI
- **Complexity**
  - Managing PKI infrastructure is technically demanding
- **Trust Dependence**
  - Security relies heavily on the trustworthiness of the Certificate Authority
- **Key Compromise**
  - If a private key is stolen, the associated security becomes invalid
