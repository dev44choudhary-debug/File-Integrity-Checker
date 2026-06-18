# File-Integrity-Checker

# File Integrity Checker using Java

## Overview

This project is a File Integrity Checker developed in Java. It uses the SHA-256 cryptographic hash function to verify whether a file has been modified after its hash was originally generated.

## Features

* Generate SHA-256 hashes for files
* Store hash values for future verification
* Compare current and stored hashes
* Detect file modifications
* Simple command-line interface

## Technologies Used

* Java
* SHA-256
* Java File I/O
* MessageDigest API

## How It Works

1. User selects a file.
2. The program generates a SHA-256 hash.
3. The hash is stored in a .hash file.
4. When the file is checked again, a new hash is generated.
5. The stored hash and current hash are compared.
6. The program reports whether the file integrity is maintained.

## Project Structure

File-Integrity-Checker-Java/
├── src/
│   └── FileIntegrityChecker.java
├── screenshots/
├── README.md



## Applications

* File integrity verification
* Cybersecurity monitoring

## Future Enhancements

* SHA-512 support
* SHA3-256 support
* Folder integrity checking
* RSA digital signatures
* Java Swing GUI

## Author

Dev Choudhary


