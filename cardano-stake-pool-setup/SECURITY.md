# Security Policy

Security and operator ownership are fundamental to every Blockiy stake pool setup.

The operator must remain the sole owner and controller of all wallets, private keys, server accounts, and pool rewards.

## Core Security Principles

### Operator Ownership

The operator owns:

* Wallets and wallet recovery information
* Payment addresses and rewards
* Cold keys
* VRF keys
* KES keys
* Hosting-provider accounts
* Server accounts
* Domain names and external-service accounts

Blockiy does not take custody of ADA, wallets, keys, rewards, or hosting accounts.

### Private Keys Stay Private

Blockiy never requests, receives, stores, or transmits:

* Wallet seed phrases or recovery phrases
* Payment signing keys
* Cold signing keys
* VRF signing keys
* KES signing keys
* Encrypted key files
* Key passphrases
* Server passwords or root passwords
* Private API keys, secret tokens, or recovery codes

Do not send any of these items through email, Telegram, GitHub, support tickets, cloud storage, screenshots, or any other communication channel.

### Public Information May Be Shared

Where required for deployment or verification, the operator may share non-sensitive public information, such as:

* Pool ID
* Pool ticker
* Public verification keys
* Public payment or reward addresses
* Public relay addresses
* Public DNS records
* Public pool metadata
* Non-sensitive server information

A public verification key is not the same as a private signing key. If unsure, do not share the file or value until it has been confirmed as safe.

## Secure Server Access

When Blockiy requires server access for deployment or support, the operator should create a dedicated temporary account.

Recommended practice:

* Use SSH public-key authentication instead of passwords
* Create a separate user only for the agreed work
* Grant only the permissions required for deployment
* Restrict access by IP address where practical
* Keep access active only for the necessary period
* Remove the temporary account or access permission after handover
* Review server access logs after work is completed

Blockiy should never need the operator's personal hosting password, root password, or recovery credentials.

## Sensitive Key Operations

All key-generation, signing, and wallet actions must be completed by the operator under their own control.

Blockiy may provide instructions and explain the workflow, but the operator must generate and protect private keys locally.

For verification, share only public keys, public hashes, pool IDs, or command output that does not expose secret material.

## Backups and Recovery

Blockiy can provide backup and recovery guidance, but does not hold the operator's key backups or wallet recovery information.

Configuration backups must exclude:

* Private key files
* Wallet files
* Seed phrases
* Password files
* API secrets
* Recovery codes

The operator is responsible for maintaining secure, tested backups of all sensitive recovery information.

## Communication Rules

For all project communication:

* Use official Blockiy contact channels only
* Confirm unusual requests before acting on them
* Do not send secrets through chat applications or email
* Do not open unknown files claiming to be pool keys or updates
* Report suspected phishing or unauthorized-access attempts immediately

Official support contact: [support@blockiy.com](mailto:support@blockiy.com)

## If You Suspect a Security Issue

If a private key, password, or recovery phrase may have been exposed:

1. Revoke temporary server access immediately.
2. Change affected hosting and server credentials.
3. Rotate compromised credentials where possible.
4. Contact the relevant hosting provider if account access may be affected.
5. Do not continue using a wallet or key that may be compromised.
6. Contact Blockiy for non-custodial technical guidance.

Blockiy cannot recover exposed, lost, or compromised private keys, seed phrases, wallets, or funds.
