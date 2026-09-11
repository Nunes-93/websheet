# Websheet

**Build Excel apps with HTML screens.** You design the screen like a web page,
Excel stays the spreadsheet and the database, and what you hand over is a single
file.

## Download

**[⬇ Download the latest version](https://github.com/Nunes-93/websheet/releases/latest)**

The installer is per-user — it never asks for an administrator and never touches
anyone else's Windows. After installing, the **New project** wizard shows up in
the Start menu.

> Windows may show a SmartScreen warning the first time, because the installer is
> not signed yet. Choose **More info → Run anyway** and it continues normally.

## What you need

- **Windows 10 or 11**
- **Excel** installed (32-bit or 64-bit — both work)
- **WebView2**, which ships with Windows 11 and with most Windows 10 installs

## How it works

Your screens are plain HTML, CSS and JavaScript running in a WebView2 inside an
Excel form. VBA is only the plumbing between them, and the business rules are
compiled into a DLL — so what you deliver does not carry your logic in readable
form.

You never start from a blank file: drop your own workbook in, and the project is
built around the sheets you already have.

## Versions

Every version is listed under
[Releases](https://github.com/Nunes-93/websheet/releases), with what changed.
The installed kit tells you on its own when a new one is out.

## About this repository

This holds **the distribution only**: the installer and the file that says which
version is current. The framework's source code is not public.
