# Installing GageMate on Windows

## Before installation

- Use a supported Windows computer. The installer is intended for Windows; specific tested Windows versions and hardware requirements should be confirmed in the release notes.
- Download the installer from this repository's [Releases](../../releases) page.
- Confirm the filename and version against the release notes.
- If a SHA-256 checksum is provided, compare it with your download.

In Windows PowerShell, run:

```powershell
Get-FileHash -Algorithm SHA256 .\GageMate_Setup_1.3.0.exe
```

Compare the output with the published checksum; the values must match exactly.

## Install

1. Close any running copy of GageMate.
2. Run `GageMate_Setup_1.3.0.exe`.
3. Read and accept the EULA if you agree to its terms.
4. Follow the installer prompts to finish installation.
5. Start GageMate from the Start menu or installed shortcut.

The packaged installer does not require you to separately install Python.

## Windows security prompts

Windows SmartScreen or antivirus software may flag a new or less widely downloaded application, particularly if the installer is not code-signed. **Do not disable security protections or bypass a warning automatically.** Check that the download came from the official release, compare its checksum, and contact the publisher if you cannot verify it.

## Updates

Download the newest installer from Releases and read its release notes. Back up any locally stored datasets or exports before upgrading. Close the application before installing an update.

## Troubleshooting

If installation or launch fails, include your Windows version, GageMate version, the exact error text, and reproduction steps in a [support issue](../../issues). Do not upload confidential datasets.
