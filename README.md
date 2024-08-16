# Secure Distributed File Sharing System

## Project Overview

This project implements a secure, distributed file-sharing system. The system allows users to authenticate, upload, download, and manage files across multiple servers while ensuring data security and access control through token-based authentication.

## Features

- **Token-Based Authentication**: Secure user login and session management using tokens.
- **Server-Specific Tokens**: Tokens are tied to specific servers, preventing misuse across different servers.
- **Group-Based Access Control**: Users can be part of groups, and file access is managed based on group membership.
- **Encryption**: Data transmission is encrypted to protect against unauthorized access.
- **HMAC for Integrity**: Hash-based Message Authentication Code (HMAC) ensures the integrity of tokens and communications.

## Components

- **Authentication Server**: Manages user authentication, token generation, and group memberships.
- **Host Server**: Manages file storage and ensures that only authorized users can access files.
- **Client Application**: Allows users to connect to the servers, authenticate, and perform file operations.

