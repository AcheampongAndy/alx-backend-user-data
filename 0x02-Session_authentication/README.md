# 0x02. Session Authentication

## Project Overview
This project involves implementing a Session Authentication mechanism in Python without using external libraries. The aim is to understand the core concepts of session-based authentication by building a system that stores session data on the server and uses cookies to track authenticated users.

## Learning Objectives
By the end of this project, you should be able to:
- Explain the purpose of authentication and session authentication.
- Describe what cookies are and how they’re used in session management.
- Send and parse cookies for maintaining sessions between client and server.

## Key Concepts

### Authentication and Session Authentication
- **Authentication**: The process of verifying a user's identity before granting access to certain resources.
- **Session Authentication**: A method of authentication where a session ID is created and stored server-side upon successful login. This ID is sent back and forth using cookies to maintain a persistent session for the user.

### Cookies
- **Cookies**: Small pieces of data stored on the client’s browser, used in this project to hold session identifiers, enabling the server to recognize authenticated users across requests.

## Requirements

- **Python Version**: All code will be executed on Ubuntu 18.04 LTS using Python 3.7.
- **Code Style**: Follow `pycodestyle` style guidelines (version 2.5).
- **Executable Files**: Ensure all files have executable permissions.
- **Documentation**: All modules, classes, and functions must be documented with sentences that explain their purpose. These will be verified for completeness and clarity.

## Project Files

Each file in this project should:
1. Start with the shebang `#!/usr/bin/env python3`.
2. Be compatible with Python 3.7 on Ubuntu 18.04 LTS.
3. Include a new line at the end.
4. Be written following `pycodestyle` guidelines.

