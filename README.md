# Enterprise Management

Three-project VB6 enterprise logon suite: Winsock logon client (`Logon Client.exe`) that contacts `%LOGONSERVER%` on port 1001 and receives drive/printer mapping data; matching logon server (`Logon Server.exe`); and a User Management project for account work. Client UI steps through contact, send request, receive data, disconnect, then mapping drives/printers.

**Source last updated:** 2026-08-27 · **Language:** VB6 · **Target:** VB6 Win32 · **Output:** WinForms exe (3 projects)

_Note: original OneDrive LastWriteTime values were wiped to 2026-08-27 by a zip transfer; date above uses best available evidence (headers/copyright where helpful)._

## Solution structure

| Project | Language | Type | Purpose |
|---------|----------|------|---------|
| `Client` (`Logon Client/Logon Client.Vbp`) | VB6 | WinForms exe | Winsock logon client |
| `UserMan` (`User Management/User Management.vbp`) | VB6 | WinForms exe | User management UI |
| `Server` (`Logon Server/Logon Server.Vbp`) | VB6 | WinForms exe | Winsock logon server |

## How to open

Open the `.vbp` in Visual Basic 6.0 IDE:
- `Logon Client/Logon Client.Vbp`
- `User Management/User Management.vbp`
- `Logon Server/Logon Server.Vbp`

## Requirements

- Visual Basic 6.0 IDE
- Registered OCX/DLL dependencies referenced by the `.vbp` (may need to be installed separately):
  - `MSCOMCTL.OCX`
  - `MSWINSCK.OCX`
  - `TABCTL32.OCX`

## Attribution and provenance

Working copy from Dave Robinson's OneDrive Historical Dev folder `VB/Old/Enterprise Management`.
Company names in project files: Unknown Organization.

## License

MIT © 2026 VaderConsulting for Dave Robinson's code. See `LICENSE`.
