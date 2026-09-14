# MOOGH Scoop Bucket

Scoop bucket for [MOOGH](https://www.aimoogh.com/) - the AI agent desktop client for Windows 10/11.

## Install

```powershell
scoop bucket add moogh https://github.com/youlemei2022-web/scoop-moogh
scoop install moogh
```

## Update

```powershell
scoop update
scoop update moogh
```

## Uninstall

```powershell
scoop uninstall moogh
```

## About

MOOGH is an AI agent desktop client. Describe a task and MOOGH plans it, asks for
your approval, then executes it on your own PC: file operations, command execution,
coding fixes and routine automation.

MOOGH is in open testing. There is no subscription - you pay only for actual usage,
with transparent top-ups (1 USD = 60 points) and no hidden fees.

## Links

- Site: https://www.aimoogh.com/
- Download: https://agent.aimoogh.com/download
- Support: support@aimoogh.com
- Terms of Service: https://agent.aimoogh.com/terms.html
- Privacy Policy: https://agent.aimoogh.com/privacy.html

## Notes

- The package is the official Authenticode signed build (Certum Code Signing 2021 CA).
- Scoop extracts the NSIS payload into the app directory: no installer is run and no registry entries are written.
- Everything MOOGH needs lives in the app directory, so `scoop uninstall moogh` removes it completely.