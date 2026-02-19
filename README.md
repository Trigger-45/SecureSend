# 🔐 SecureSend

**Zero-Knowledge File Encryption in Your Browser**

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![Live Demo](https://img.shields.io/badge/demo-live-success)](https://trigger-45.github.io/SecureSend)
[![GitHub Pages](https://img.shields.io/badge/GitHub-Pages-green)](https://pages.github.com/)

> A privacy-focused, client-side file encryption tool that runs entirely in your browser. No servers, no tracking, no data storage.

---

## ⚠️ Disclaimer

**THIS SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND.**

- This is an experimental educational project
- **NOT** recommended for highly sensitive or classified documents
- No guarantee against security vulnerabilities
- Users accept all risks when using this tool
- The developer assumes no liability for data breaches, encryption failures, or any other damages
- Always maintain secure backups of important data
- Use at your own risk

For critical security needs, consult professional security solutions.

## ✨ Features

- **RSA-4096 Key Generation** - Military-grade encryption keys generated in your browser
- **File Encryption** - Encrypt any file for specific recipients using their public key
- **File Decryption** - Decrypt files sent to you using your private key
- **Zero-Knowledge Architecture** - All operations happen client-side
- **No Data Storage** - Nothing is ever uploaded, tracked, or stored
- **Downloadable Keys** - Export your keys as text files for safekeeping
- **No Backend Required** - Pure HTML/CSS/JavaScript
- **Cross-Platform** - Works on desktop, mobile, and tablets
- **Open Source** - Fully auditable code

---

## 🎯 Use Cases

- Send sensitive documents securely
- Share confidential contracts
- Exchange medical records privately
- Transfer business documents safely
- Maintain end-to-end encryption without third parties

---

## 🚀 Quick Start

### For Recipients (Receiving Encrypted Files):

1. **Generate Your Keys**
   - Go to the [Generate Keys](https://trigger-45.github.io/SecureSend) tab
   - Click "Generate New Key Pair"
   - Download both `public_key.txt` and `private_key.txt`
   - ⚠️ **Keep your private key secret!**

2. **Share Your Public Key**
   - Send your `public_key.txt` to people who want to send you encrypted files
   - You can share this via email, WhatsApp, etc. - it's safe!

3. **Decrypt Files**
   - When you receive an encrypted `.bin` file:
   - Go to the "Decrypt" tab
   - Paste your private key
   - Select the encrypted file
   - Click "Decrypt File"
   - Your original file will be downloaded

### For Senders (Encrypting Files):

1. **Get Recipient's Public Key**
   - Ask the recipient to send you their `public_key.txt`

2. **Encrypt a File**
   - Go to the "Encrypt" tab
   - Paste the recipient's public key
   - Select the file you want to encrypt
   - Click "Encrypt File"
   - An encrypted `.bin` file will be downloaded

3. **Send the Encrypted File**
   - Send the `.bin` file to the recipient
   - Only they can decrypt it with their private key!

