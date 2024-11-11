# 0x01. Basic Authentication

## Overview
This project is focused on understanding and implementing **Basic Authentication** in a simple API. Authentication is a crucial part of API security, enabling verification of user identity. While in production environments, developers typically use established libraries and frameworks (e.g., Flask-HTTPAuth), here we will implement each part manually to gain a thorough understanding of the process.

## Learning Objectives
By the end of this project, you will be able to explain:
- **What authentication is** and why it’s important.
- **What Base64 encoding** is and how to use it.
- How to encode a string in **Base64**.
- The concept of **Basic Authentication** and how it works.
- How to send the **Authorization header** in HTTP requests.

### Python Scripts
- **Environment**: Ubuntu 18.04 LTS
- **Python version**: 3.7
- **Coding style**: Follow `pycodestyle` (version 2.5)

### Project Files
- **README.md**: This description file.
- **Python files**: All scripts must:
  - Begin with `#!/usr/bin/env python3`.
  - End with a new line.
  - Be executable and use PEP8/pycodestyle formatting.
  - Include documentation for each module, class, and function.

## Project Instructions

1. **Base64 Encoding**: Learn how to encode and decode strings in Base64, which is used for transmitting authorization data in HTTP headers.

2. **Basic Authentication**: Implement Basic Authentication by encoding the `username:password` format in Base64 and adding it to the `Authorization` header of HTTP requests.
