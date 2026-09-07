# ClarityNote Model Releases

Official public release channel for approved ClarityNote Clinical model packages.

## Published here

- Signed and versioned model packages
- Model manifests and SHA-256 checksums
- Runtime and hardware compatibility metadata
- Release notes and documented rollback information
- Approved validation summaries and third-party notices

Stable release discovery endpoint:

`https://api.github.com/repos/ClarityNoteAI/claritynote-model-releases/releases/latest`

## Never publish here

Training datasets, PHI, contributed examples, source notes, reviewer identities, private evaluation records, credentials, signing keys, or unapproved checkpoints and adapters.

Only a package that passes the governed privacy, clinical evaluation, release-approval, signing, and device-verification process may be published. Field installations must verify the manifest signature and checksums before activation.