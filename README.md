# Stewardship

**A free desktop application for Local Spiritual Assembly treasurers.**

Stewardship helps an LSA treasurer keep the books: record contributions and
expenses across funds, issue contribution receipts, reconcile the bank
statement, and produce the monthly reports, the annual **NSA Treasurer's
Financial Report**, and a complete **auditor's package** at year-end. It follows
the Bahá'í 19‑month fiscal year and NSA guidelines.

It runs entirely on your own computer — **no internet connection, no cloud, no
account.** Your Assembly's records never leave your machine.

> 📥 **[Download the latest version →](https://github.com/bpamiri/stewardship-releases/releases/latest)**

<!-- Screenshot goes here once available: ![Stewardship](docs/screenshot.png) -->

---

## What it does

- **Ledger & funds** — record income and expenses, split a single contribution
  across multiple funds (the Local Fund, the national and international Bahá'í
  funds the Assembly transmits, earmarked gifts, …).
- **Contribution receipts** — issued automatically when you record a deposit,
  numbered in sequence, and printable/savable as PDF.
- **Bank reconciliation** — match your records to the bank statement each month;
  outstanding checks and deposits carry forward year to year.
- **Imports** — pull in OCS (Online Contribution System) holding-account activity
  and your membership roster from the eMembership export, so you don't retype them.
- **In-kind contributions** — record non-cash gifts for the record.
- **Monthly reports** — Statement of Activities and Balance Sheet as clean PDFs.
- **Year-end** — fill the official **NSA Treasurer's Financial Report** and
  generate a full **auditor's package** for your Assembly's annual audit.
- **One file per fiscal year** — each year is a self-contained snapshot, kept in
  your Documents folder, easy to back up and hand to an auditor.
- **Automatic updates** — the app checks for new versions on launch and offers to
  update with one click.

---

## Download & install

Go to the **[latest release](https://github.com/bpamiri/stewardship-releases/releases/latest)**
and download the file for your system.

### macOS  (Apple Silicon & Intel)

1. Download **`Stewardship_…_universal.dmg`**.
2. Open the downloaded `.dmg`.
3. Drag the **Stewardship** icon into your **Applications** folder.
4. Open it from Applications (or Launchpad).

The macOS build is signed and notarized by Apple, so it opens normally. (If macOS
is ever cautious on the very first launch, right-click the app → **Open** once.)

### Linux

Pick whichever matches your distribution from the
[latest release](https://github.com/bpamiri/stewardship-releases/releases/latest):

- **`…amd64.AppImage`** — works on most distributions. Make it executable, then
  run it:
  ```bash
  chmod +x Stewardship_*_amd64.AppImage
  ./Stewardship_*_amd64.AppImage
  ```
- **`…amd64.deb`** — Debian / Ubuntu: `sudo apt install ./Stewardship_*_amd64.deb`
- **`…x86_64.rpm`** — Fedora / RHEL: `sudo dnf install ./Stewardship-*.x86_64.rpm`

### Windows

Not available yet — a Windows build is planned. For now, use macOS or Linux.

---

## Keeping it up to date

Stewardship updates itself. When you open the app and a newer version is
available, you'll see a small prompt — click to install, and the app restarts on
the new version. It never updates in the background mid-session.

You can also check anytime from **Settings → Check for updates**, or just
download the newest installer from the
[releases page](https://github.com/bpamiri/stewardship-releases/releases/latest).

---

## Your data & privacy

- Everything stays **on your computer**. There is no cloud, no sign-in, and the
  app works fully offline.
- Your records are stored as one file per fiscal year, by default under
  `Documents/Bahai/<fiscal year>/`. You choose where, and you control the backups.
- The first time you open the app, a short setup wizard helps you create your
  Assembly's first data file. Prior-year history is entered by hand — a good way
  to get familiar with the app.

Treat your Assembly's records as confidential, per the NSA Stewardship Manual.

---

## About

Stewardship is provided free of charge for use by Local Spiritual Assemblies.
This repository hosts the public installers and the auto-update manifest only;
the application's source code is maintained privately.

Found a problem or have a suggestion? Contact whoever shared the app with you, or
the developer.
