# PairOnce security

PairOnce — browser-to-browser file transfer between your devices. No app, no account, files never stored on a server.

[PairOnce](https://paironce.com) is a free web app for sending files, photos, text and links between your own devices
(iPhone, Android, Windows, Mac, Linux) with no app to install and no account. The two browsers connect directly and
end-to-end encrypted (AES-256-GCM, keys from P-256 ECDH, a 13-digit safety code to compare); when a network blocks a direct
connection, an encrypted relay passes on data it cannot read. Devices on the same Wi-Fi find each other on their own, and a
large file resumes after a dropped connection. PairOnce keeps no copy. Overview: [github.com/paironce](https://github.com/paironce)
· guides: [paironce.com/guides](https://paironce.com/guides/).

- [SECURITY.md](SECURITY.md): how to report a vulnerability, and what is in scope
- [RELEASES.md](RELEASES.md): each production release and the [@paironce/core](https://github.com/paironce/core) version it runs

The threat model is in [paironce/protocol](https://github.com/paironce/protocol/blob/main/threat-model.md).

Licensed under [CC BY 4.0](LICENSE).
