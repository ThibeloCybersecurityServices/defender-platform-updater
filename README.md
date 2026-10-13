# Microsoft Defender Platform Updater

Public binary distribution maintained by Thibelo Cybersecurity Services.

## Latest release

Version **1.6.1**

Download: https://github.com/ThibeloCybersecurityServices/defender-platform-updater/releases/tag/v1.6.1

## Installation

Download the MSI for your Windows architecture (x86, x64 or ARM64).
Verify each MSI SHA-256 against SHA256SUMS.txt before installation.

The packages in this release are **unsigned**. SHA-256 verifies integrity against the accompanying manifest; it does not provide Authenticode publisher verification.

## Validation and limitations

- Version 1.6.1 x64 MSI upgrade from 1.6.0 passed the full 12/12 Windows lifecycle checks.
- Full Windows PowerShell 5.1 and PowerShell 7 Pester suites and PSScriptAnalyzer passed for the released candidate.
- MSI build, architecture metadata and hash checks passed for all three architecture packages.
- Native x86 and ARM64 installation lifecycle, Intune LocalSystem pilot, and genuinely degraded/legacy device tests remain **deferred**, not passed.
- The Intune remediation script requires a previously installed **trusted 1.6.1+ MSI**.

This repository distributes approved binary release artifacts only. It does not contain the private development history.
