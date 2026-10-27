# Tab Launcher Clone

A locked Windows desktop launcher distributed to approved team members.

## Download

Go to the [Releases](https://github.com/junaidaliniz56-cell/tab-launcher-clone/releases/latest) page.

| Asset | Purpose |
| --- | --- |
| `Tab Launcher Clone Setup 1.0.2.exe` | Recommended installer |
| `Tab Launcher Clone 1.0.2.exe` | Portable backup |
| `README-TEAM.txt` | Quick install notes for team members |
| `SHA256SUMS.txt` | Checksums for both executables |
| `LICENSE*`, `THIRD_PARTY_NOTICES.md` | Application and third-party licenses |

## Requirements

- Windows 10 or Windows 11, 64-bit
- Internet connection for Firebase access checks
- An approved team email address

## Install

1. Download the setup file.
2. Run it and complete the installation.
3. Open the app from the Desktop shortcut or Start Menu.
4. Enter the launch password provided by the owner.
5. Log in with your approved team email.

## Verify the download

Compare the SHA-256 checksum of each file with `SHA256SUMS.txt`.

```text
639b490ac9f73ff168c48c64615d9e66bee12bd199d0a9d53eb1ac82f71671fa  Tab Launcher Clone 1.0.2.exe
4afab18dcaa8991d236ffb44ce2bc661db4f1722cbc093764d108bbc6ca900f3  Tab Launcher Clone Setup 1.0.2.exe
```

## Security

- Only approved emails can use the app.
- Admin credentials are not included in this repository or its releases.
- The app payload is AES-256 encrypted.
- Both installers prompt for a launch password and extract the app to a temporary folder only while it is running.
- Old unencrypted releases have been removed.
- Do not redistribute modified copies.
- Report security issues privately as described in `SECURITY.md`.

## Third-party licenses

This application bundles Electron and Chromium.

- Electron license: `LICENSE.electron.txt`
- Chromium and third-party license texts: `LICENSES.chromium.html`
- Summary of third-party notices: `THIRD_PARTY_NOTICES.md`
- Zstandard (zstd) license copy: [LICENSE.zstd.txt](https://github.com/junaidaliniz56-cell/tab-launcher-clone/blob/main/LICENSE.zstd.txt) (upstream: <https://github.com/facebook/zstd>)
- xxHash license copy: [LICENSE.xxhash.txt](https://github.com/junaidaliniz56-cell/tab-launcher-clone/blob/main/LICENSE.xxhash.txt) (upstream: <https://github.com/Cyan4973/xxHash>)
- Zstandard fork: <https://github.com/junaidaliniz56-cell/zstd>
- xxHash fork: <https://github.com/junaidaliniz56-cell/xxHash>

## Project files

- `CHANGELOG.md` - release history
- `CONTRIBUTING.md` - contribution and bug-report policy
- `SECURITY.md` - security policy
- `LICENSE` - usage terms for this application
- `THIRD_PARTY_NOTICES.md` - third-party license summary
- `LICENSE.electron.txt` - Electron license
- `LICENSES.chromium.html` - Chromium third-party licenses
- `LICENSE.zstd.txt` - Zstandard (zstd) license
- `LICENSE.xxhash.txt` - xxHash license

## License

The application is proprietary. See [LICENSE](LICENSE).
Third-party components remain under their own licenses; see
[THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md).
