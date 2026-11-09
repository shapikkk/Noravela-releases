# Noravela

Noravela is a desktop workspace for Windows that brings your local projects, AI coding agents (Claude Code, Codex, Gemini, Aider and others), Git changes and project memory into one fast native app.

This repository hosts the installers and the update manifest. Installed copies of Noravela update themselves from here.

## Download

Get the latest installer from **[Releases](https://github.com/shapikkk/Noravela-releases/releases/latest)**:

- `Noravela_<version>_x64-setup.exe` — recommended, installs for the current user without administrator rights.
- `Noravela_<version>_x64_en-US.msi` — for managed installations.

## Requirements

- Windows 10 or 11 (x64)
- Microsoft Edge WebView2 runtime (installed automatically if missing)
- Git; Claude Code or another agent CLI for agent features

## Notes

The installer is not yet signed with an Authenticode certificate, so Windows SmartScreen may show an "unknown publisher" warning. Choose **More info → Run anyway** to continue. Updates are verified with Noravela's own signing key before they are installed.
