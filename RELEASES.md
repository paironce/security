# Production releases

Each release of paironce.com and the core version it runs. The web app is not open source; the encryption and pairing
code it uses is [@paironce/core](https://github.com/paironce/core) at the tag below. All four repositories are tagged with
each paironce.com version, also when their content did not change.

| Date | paironce.com | @paironce/core | Notes |
| --- | --- | --- | --- |
| 2026-10-23 | 2.2.0 | [v2.2.0](https://github.com/paironce/core/releases/tag/v2.2.0) | Files up to 10 GB when one of the two devices has Pro: protocol adds `MAX_FILE_BYTES`, the `hugeFiles` and `pro` hello flags, and up to 1,048,576 chunks per file; core's binary frames accept the larger chunk index. New interface strings in locales. |
| 2026-10-23 | 2.1.2 | [v2.1.2](https://github.com/paironce/core/releases/tag/v2.1.2) | The page asks for relay credentials again after a dropped request or a server error; clearer relay message. Core code unchanged. |
| 2026-10-23 | 2.1.1 | [v2.1.1](https://github.com/paironce/core/releases/tag/v2.1.1) | Pro license dialog lists its devices and frees a lost one's slot (new interface strings in locales). Core code unchanged from v2.1.0. |
| 2026-10-23 | 2.1.0 | [v2.1.0](https://github.com/paironce/core/releases/tag/v2.1.0) | First open release. File names and types stay inside the encrypted channel when both devices are on this version (`privateMeta`). |
