# ARGUS Encrypted Update Channel

This repository is reserved exclusively for encrypted, device-bound ARGUS update payloads and public metadata.

Security contract:

- No ARGUS source code.
- No plaintext APK files.
- No signing keystore or passwords.
- No Binance, Telegram, GitHub, or other access tokens.
- Every APK is signed in the private source repository before encryption.
- Every payload is encrypted for the registered tablet public key.
- ARGUS verifies ciphertext SHA-256, plaintext SHA-256, package name, version code, and the permanent ARGUS signing certificate before requesting installation.

Current state: awaiting first tablet registration.
