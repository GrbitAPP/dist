# dist

Downloads for the Grbit app.

- **Server releases** (`vX.Y.Z`): Linux server binaries for x86_64 and aarch64,
  `SHA256SUMS`, build metadata and `RELEASE-MANIFEST.sha256` with its Sigstore
  bundle. Check a download with `sha256sum -c SHA256SUMS`.
- **Geo database** (`geo-YYYYMMDD` releases, `geo/manifest.json`): the app
  verifies the manifest's Ed25519 signature before it uses the database.

Every release is published by the `publish` workflow in this repository.
Published files are never replaced; new bytes get a new version.
