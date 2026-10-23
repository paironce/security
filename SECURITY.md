# Security policy

## Reporting a vulnerability

Email **security@paironce.com** (until that address is live: support@paironce.com, subject starting "SECURITY"). Please do
not open a public issue for a vulnerability.

Include what you found, how to reproduce it, and what an attacker gains. We answer within 3 working days, agree a fix and
disclosure date with you (normally within 90 days), and credit you in the advisory unless you prefer otherwise.

## Scope

- The protocol (`protocol` repository) and the core library (`core`, published as `@paironce/core`).
- The production service at paironce.com, for issues that break the protocol's promises (for example, reading content,
  joining a pairing without approval, or using the relay without a valid credential).

Out of scope: denial of service by volume, reports from automated scanners without a working impact, missing headers
without an exploit, and social engineering of PairOnce staff.

## Safe harbour

Research done in good faith, within this scope, that does not access other people's data or degrade the service, will not
be pursued. Use your own devices and accounts.

## Releases

Each production release of paironce.com is recorded in this repository with the `@paironce/core` version it uses.
