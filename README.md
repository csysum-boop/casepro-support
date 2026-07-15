# casepro-support

Public support and Android download materials for CasePro.

## Android release allowlist

Only publish the current signed and obfuscated APK, its SHA256 sidecar,
`latest.json`, the stable QR image, and the public support/privacy pages.
The QR image must decode exactly to the current `apkUrl`, and the download
page must version its QR image URL so phones do not reuse an older cached QR.

Never commit or upload source code, R8 mapping/seeds/usage files, signing
material, cloud credentials, private exports, real user data, or test output.
