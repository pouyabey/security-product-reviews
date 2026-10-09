# Nord Security Suite Review

This review covers the main Nord security products and how they fit into a personal security stack.

## Contents

- [NordVPN](#nordvpn)
- [NordPass](#nordpass)
- [NordLocker](#nordlocker)
- [Plans and Value](#plans-and-value)
- [How the Products Work Together](#how-the-products-work-together)
- [Security Considerations](#security-considerations)
- [Privacy and Testing Policy](#privacy-and-testing-policy)

---

## NordVPN

NordVPN is a VPN service designed to encrypt network traffic and hide the user's public IP address from websites and other services.

### Main Features

- Encrypted VPN connection
- NordLynx/WireGuard-based protocol
- Kill switch
- DNS and IP leak protection
- Threat and malicious-site protection
- Support for multiple platforms

### What It Helps Protect Against

NordVPN can reduce the visibility of browsing activity to:

- Internet service providers
- Public Wi-Fi operators
- Local network administrators
- Websites attempting to identify users primarily by IP address

A VPN does not provide complete anonymity and does not replace endpoint security, MFA, or safe browsing practices.

---

## NordPass

NordPass is a password manager for securely storing passwords, passkeys, secure notes, and other sensitive information.

### Security Architecture

NordPass uses:

- End-to-end encryption
- Zero-knowledge architecture
- XChaCha20 encryption
- Argon2id password-based key derivation
- FIDO2/WebAuthn security-key support

### Premium Features

Depending on the subscription tier, additional features may include:

- Password Health
- Data Breach Scanner
- Email Masking
- Secure Sharing
- File Attachments
- Emergency Access
- Simultaneous access across multiple devices

For users who want stronger authentication, hardware security keys can provide phishing-resistant MFA.

---

## NordLocker

NordLocker provides encrypted cloud storage.

Files are encrypted before being uploaded, making it useful for storing sensitive documents, backups, archives, and other private files.

### Possible Uses

- Important documents
- Research files
- Device configuration backups
- Photos and archives
- Recovery documents
- Encrypted off-site backups

NordLocker should be viewed primarily as encrypted cloud storage rather than a full replacement for services such as Google Drive or Microsoft OneDrive for collaboration.

It is also not a direct Time Machine backup destination for macOS.

---

## Plans and Value

Nord offers several subscription tiers that bundle different services.

### Plus

Typically includes:

- NordVPN
- Threat protection
- NordPass
- Data breach monitoring

### Complete

Includes the features of Plus and adds:

- Encrypted cloud storage

This tier can provide good value when both a VPN, password manager, and private cloud storage are useful.

### Prime

Includes the previous features and adds additional identity and financial protection services.

These may include features such as:

- Credit monitoring
- Identity theft recovery assistance
- Additional identity protection services

Pricing and bundled features change frequently, so current pricing should always be verified directly with Nord.

---

## How the Products Work Together

Each product protects a different part of the security stack:

| Product | Primary Purpose |
|---|---|
| NordVPN | Network privacy and encrypted traffic |
| NordPass | Credential and password protection |
| NordLocker | Encrypted file storage |

Together they provide multiple layers of protection, but they do not replace:

- MFA
- Software updates
- Endpoint protection
- Secure backups
- Phishing awareness
- Good account recovery practices

---

## Security Considerations

No single security product provides complete protection.

For example:

- A VPN cannot prevent credential phishing.
- A password manager cannot protect a fully compromised endpoint.
- Encrypted cloud storage cannot replace a complete backup strategy.
- MFA security depends heavily on the recovery methods configured for the account.

The strongest approach is layered security rather than relying on a single product.

---

## Privacy and Testing Policy

This repository documents product testing and security analysis, not personal security configurations.

Testing is performed using test environments or sanitized data.

This repository does not publish:

- Personal email addresses
- Passwords or credentials
- Recovery codes
- Security-key identifiers
- Device identifiers
- IP addresses
- Internal network information
- Account recovery configurations
- Production security configurations

The goal is to evaluate the products without exposing information that could be used to identify or target the tester.

---

## Disclaimer

This is an independent technical review and is not affiliated with Nord Security.

Product features, pricing, and subscription terms may change over time.
