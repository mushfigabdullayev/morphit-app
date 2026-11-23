# Security

Morphit is built to keep files on the computer: it contains no network code, opens Office files read-only with macros
off, and never overwrites an original.

## Reporting a vulnerability

Please report it privately through [GitHub's private vulnerability reporting](https://github.com/gns753/morphit-app/security/advisories/new),
not in a public issue. Include the Morphit version, the Windows version and the steps to reproduce. Please do not send
confidential files; a minimal sample file is enough.

You will get an answer within a week. Fixes ship in the next release, and the release notes credit the reporter unless
they ask otherwise.

## Supported versions

Only the latest release receives fixes. Updating is safe: run the new Setup over the old one; settings and history are
kept.

## Checking a download

Every release publishes the SHA-256 of `Morphit.Setup.exe`. In PowerShell:

```powershell
Get-FileHash .\Morphit.Setup.exe -Algorithm SHA256
```
