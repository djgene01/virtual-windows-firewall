# Virtual Windows Firewall

A free Windows Firewall manager with brute-force protection, by [Admin Software](https://www.adminsoftware.co.za).

It installs as a Windows service and gives you a local web console at `http://127.0.0.1:5080`:

- **Brute-force protection.** Watches Windows sign-in events and bans addresses that keep failing, with automatic expiry.
- **Firewall rules.** An inventory of Windows Firewall rules, plus allowlists, bans and open-port views.
- **Remote Desktop protection.** Settings to restrict who can reach RDP.
- **Analytics and reports.** Charts of blocked activity, with PDF reports you can email on a schedule.

Everything runs on your own computer. The console listens on this computer only by default, and no data is sent to Admin Software.

## Download

Get the latest installer from [Releases](../../releases/latest). Each release lists the file's SHA-256 checksum.

The installer and the program are digitally signed. Windows shows the verified publisher as **Tech-on,Tech-off (Pty) Ltd**, the company that holds Admin Software's code-signing certificate.

## Install

1. Run the `.msi` as an administrator, on 64-bit Windows 10 (version 1607 or later), Windows 11, or Windows Server 2016 or later.
2. When it finishes, open `http://127.0.0.1:5080` (a desktop shortcut is created) and create the first administrator account.

Keep another way to reach any remote computer (for example console access) while you set up allowlists and bans.

## Licence

Free to use, for personal and business use, under the licence shown in the installer. You may share the unmodified installer, but not sell it. The source code is not published.

## Support

Questions and feedback: eugene.bosman@adminsoftware.co.za
