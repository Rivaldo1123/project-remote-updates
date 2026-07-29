# Project Remote downloads

This public repository contains Project Remote Windows binaries, checksums, and
release metadata only. It does not contain application source code.

Download builds from [Releases](../../releases). Each release provides:

- A per-user Windows x64 installer.
- A self-contained portable Windows x64 ZIP.
- A SHA-256 checksum manifest for both downloads.

Verify a download in PowerShell:

```powershell
Get-FileHash .\ProjectRemote-Setup-x64-<version>.exe -Algorithm SHA256
```

Compare the result with the matching entry in the release checksum manifest.

Alpha builds are unsigned and Windows SmartScreen may display a warning. They
are intended for owner testing; authenticated live-RDP production acceptance is
not yet complete.

