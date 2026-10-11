# netremotetod

VB6 demo (project Project1, form `NetRemoteTod`) for the NetAPI32 `NetRemoteTOD` call. On button click it requests a remote server TIME_OF_DAY buffer, converts elapsed seconds since 1970-01-01 with timezone adjustment, and prints the remote date beside the local clock for comparison. Company field in the VBP is Microsoft; server name is a placeholder (`\\Your Server!`).

**Source last updated:** 2026-08-27 · **Language:** VB6 · **Target:** VB6 Win32 · **Output:** WinForms exe

_Note: original OneDrive LastWriteTime values were wiped to 2026-08-27 by a zip transfer; date above uses best available evidence (headers/copyright where helpful)._

## Solution structure

| Project | Language | Type | Purpose |
|---------|----------|------|---------|
| `Project1` (`NetRemoteTOD.vbp`) | VB6 | WinForms exe | NetRemoteTOD remote time-of-day demo |

## How to open

Open the `.vbp` in Visual Basic 6.0 IDE:
- `NetRemoteTOD.vbp`

## Requirements

- Visual Basic 6.0 IDE
- Network access to call NetRemoteTOD against a reachable host

## Attribution and provenance

Working copy from my Historical Dev folder `VB/Old/netremotetod`.
Company names in project files: Microsoft.

## License

MIT (c) 2026 Vader Consulting for Dave Robinson's code. See `LICENSE`.
