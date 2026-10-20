# YoYo Clone Manager downloads

**Experimental debug build — Android 17 is not fully qualified.**

Latest experimental build: **task-retention C2 (2026-10-20)**.

- [Download APK](https://github.com/ko-htut/yoyo-clone-manager-downloads/releases/download/v0.4-20261020-task-retention-c2a4cc5a/YoYoCloneManager-0.4-task-retention-UNQUALIFIED-c2a4cc5a.apk)
- [Download release](https://github.com/ko-htut/yoyo-clone-manager-downloads/releases/tag/v0.4-20261020-task-retention-c2a4cc5a)
- [QR image](https://github.com/ko-htut/yoyo-clone-manager-downloads/releases/download/v0.4-20261020-task-retention-c2a4cc5a/YoYoCloneManager-download-QR.png)
- [Known limitations](https://github.com/ko-htut/yoyo-clone-manager-downloads/releases/download/v0.4-20261020-task-retention-c2a4cc5a/NOTICE.txt)
- [SHA-256 checksums](https://github.com/ko-htut/yoyo-clone-manager-downloads/releases/download/v0.4-20261020-task-retention-c2a4cc5a/SHA256SUMS.txt)

The Manager task-retention change passed 10/10 targeted checks on the recorded
official Android 17 Pixel 10 Pro Fold emulator. This is not full Android 17
compatibility. A separate original-app/distinct-package follow-up passed
another 10/10 targeted checks (20 targeted checks across two suites). Original
and guest unsaved pages and task/process identities survived Home/Recents/Open
switching without Save, Remove or force-stop. This is background task
switching; simultaneously visible split-screen windows were not tested.

Intermittent WebView disk-save failure remains unresolved; full
regression/resource/display/soak gates and physical Pixel 10 Pro Fold checks
are incomplete. Financial-app and general Google-dependent app compatibility
are unverified.

Package `com.yoyo.fixtureengine`, v4/0.4, min SDK 23 / target 28 / compile 35,
arm64-v8a, Android debug signed. Use disposable test instances.

APK SHA-256: `c2a4cc5a5aced837646fa4d63098628469dfac229f35ec01b5017a5f115d4e54`

Historical releases remain available from the repository release history.
