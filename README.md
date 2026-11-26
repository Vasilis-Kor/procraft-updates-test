# ProCraft TEST update channel (`test-auto`)

Update channel for **ProCraft TEST builds only**, used to validate automatic remote updates on test machines with synthetic data.

- Not a production channel. Production installations do not read this repository and do not accept its manifests.
- `test-auto/latest.json` is signed with a TEST-only Ed25519 key. The application checks the signature, the channel, the version and the SHA-256 of the installer before it installs anything.
- Installers are attached to the GitHub Releases of this repository.

Do not use these builds in a shop.
