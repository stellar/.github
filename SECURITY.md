# Security Policy

The Stellar Development Foundation (SDF) runs a bug bounty program for many of its open source
projects, including [Stellar Core](https://github.com/stellar/stellar-core/).

For more details on the program and how to report a vulnerability, please visit [our bug bounty
page](https://stellar.org/grants-and-funding/bug-bounty).# Security Policy

## EHEPS Stellar Wallet Integration

EHEPS takes the security of its Stellar wallet integration, blockchain indexing services, donation reconciliation systems, and related infrastructure seriously.

The EHEPS Stellar Wallet integration uses Stellar network infrastructure and Horizon API services to retrieve blockchain data. EHEPS does not represent itself as an official Stellar Development Foundation product.

### Reporting a Vulnerability

If you discover a security vulnerability in the EHEPS Stellar Wallet integration, please report it privately through the security reporting mechanism configured for the EHEPS repository.

Do not publicly disclose sensitive vulnerability details before EHEPS has had an opportunity to investigate and remediate the issue.

### Wallet Security

Never disclose or commit:

- Stellar secret keys
- Private signing credentials
- API credentials
- Encryption keys
- Database credentials
- Cloud service credentials
- Authentication tokens

Public Stellar addresses and transaction hashes are not secret credentials, but applications should still handle transaction and donor information according to applicable privacy and security requirements.

### Transaction Security

EHEPS production systems should:

- Validate the Stellar network before processing transactions.
- Verify transaction and operation success.
- Validate destination accounts.
- Validate asset codes and issuers.
- Prevent duplicate transaction processing.
- Maintain audit logs.
- Protect signing infrastructure.
- Separate Testnet and Mainnet environments.
- Persist required blockchain records for reconciliation.
- Investigate failed transactions before retrying them.

### Third-Party Stellar Security Reporting

Security vulnerabilities affecting Stellar Development Foundation infrastructure or Stellar open source projects should be reported according to the applicable Stellar Development Foundation security and bug bounty procedures.

For the official Stellar Development Foundation bug bounty information, see:

https://stellar.org/grants-and-funding/bug-bounty

For vulnerabilities specifically affecting the EHEPS integration, use the security reporting mechanism provided by the EHEPS repository.

## Scope

This policy applies to EHEPS-maintained software and infrastructure implementing or integrating with Stellar and Horizon, including:

- EHEPS Stellar Wallet services
- Horizon API integrations
- Stellar donation monitoring
- Transaction reconciliation
- Blockchain indexing services
- EHEPS administrative interfaces
- Related backend services and APIs.
- https://stellar.expert/explorer/public/tx/f9d806e098ddb4596e56e2e60a776dbae0c6ca2329f5a276b9abf8edf3fa99ce
