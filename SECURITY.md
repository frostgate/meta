# Security Policy

## Supported Versions

We release patches for security vulnerabilities. Which versions are eligible for receiving such patches depends on the CVSS v3.0 Rating:

| Version | Supported          |
| ------- | ------------------ |
| 0.1.x   | :white_check_mark: |
| < 0.1   | :x:                |

## Reporting a Vulnerability

Please report (suspected) security vulnerabilities to **[security@frostgate.tech](mailto:security@frostgate.tech)**. You will receive a response from us within 48 hours. If the issue is confirmed, we will release a patch as soon as possible depending on complexity but historically within a few days.

## Disclosure Policy

When we receive a security bug report, we will assign it to a primary handler. This person will coordinate the fix and release process, involving the following steps:

* Confirm the problem and determine the affected versions.
* Audit code to find any potential similar problems.
* Prepare fixes for all still-maintained versions of Frostgate.
* Release new security fix versions of all supported versions.

## Comments on this Policy

If you have suggestions on how this process could be improved please submit a pull request.

## Security Considerations

### Zero-Knowledge Proofs

Our zero-knowledge proof system is designed to be quantum-resistant and uses state-of-the-art cryptographic primitives. However, please note:

* The security of the system depends on the soundness of the underlying ZK proving system
* Proofs should be verified using the official verifier contracts/pallets
* Custom proof generation should follow the security guidelines in our documentation

### Chain Adapters

When implementing or using chain adapters:

* Always validate chain-specific parameters
* Use secure RPC endpoints
* Implement proper error handling
* Follow chain-specific security best practices

### Message Handling

For secure message handling:

* Validate all message fields
* Check nonce values to prevent replay attacks
* Verify proofs before processing messages
* Implement proper error recovery

### Key Management

* Store private keys securely
* Use environment variables for sensitive data
* Rotate keys regularly
* Monitor for unauthorized access


## Security Contacts

* Security Email: security@frostgate.tech
* Discord: https://discord.gg/cFZeVnQ8PB
* Twitter: @frostgate 