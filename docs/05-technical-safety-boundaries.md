# Technical Safety Boundaries

## Research architecture
Keep identity presentation, legal eligibility determination, anonymous authorization, ballot handling, tally and public audit in separate trust domains.

## Wallets
EUDI and national wallet integration begins with documentation review and test credentials. A wallet proves selected attributes; it does not itself establish electoral eligibility or solve ballot secrecy, coercion or device compromise.

## Cryptography
Evaluate published anonymous-credential, blind-signature, zero-knowledge, mixnet and threshold-cryptography designs only through qualified review. Do not invent primitives or combine protocols without a formal threat model and security proof review.

## Release gates
No real election use until legal authorization, independent cryptographic and security audits, public verifiability, accessibility evaluation, coercion analysis, operational resilience, incident response, independent election administration and non-digital alternatives are demonstrated.

## Blockchain
Do not put voter identities, eligibility records or ballots on a public blockchain. Distributed ledgers are not a substitute for election law, secrecy or independent scrutiny.