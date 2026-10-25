<div align="center">

# YamYam VPN

### Free Android VPN — No Signup Required

**A lightweight Android VPN focused on simple connectivity, modern connection technologies, split tunneling, DNS protection, and transparent privacy information.**

<br>

<a href="https://play.google.com/store/apps/details?id=com.yamyam.vpn"><img alt="Get it on Google Play" src="https://play.google.com/intl/en_us/badges/static/images/badges/en_badge_web_generic.png" width="240"></a>

<br>

[![Android](https://img.shields.io/badge/Android-7.0%2B-success?logo=android)](https://yamyamvpn.top/download/)
[![Platform](https://img.shields.io/badge/Platform-Android-blue)](https://yamyamvpn.top/)
[![Price](https://img.shields.io/badge/Price-Free-brightgreen)](https://yamyamvpn.top/)
[![Signup](https://img.shields.io/badge/Signup-Not%20Required-blueviolet)](https://yamyamvpn.top/)
[![License](https://img.shields.io/badge/Software-Proprietary-lightgrey)](#source-code-status)

<br>

[**Official Website**](https://yamyamvpn.top/) ·
[**Download for Android**](https://yamyamvpn.top/download/) ·
[**Privacy Policy**](https://yamyamvpn.top/privacy/) ·
[**Documentation**](https://yamyamvpn.top/blog/)

</div>

---

## Overview

**YamYam VPN** is a free VPN application built specifically for Android users.

The project focuses on making VPN connectivity straightforward: install the app, choose a connection mode, and connect — without requiring an account, email address, phone number, username, or password.

YamYam VPN supports modern connection technologies including **VLESS, Reality, and XHTTP**, together with Android-focused features such as **split tunneling** and **DNS protection**.

> **YamYam VPN does not require account registration before use.**

**Official domain:**  
https://yamyamvpn.top/

**Official GitHub organization:**  
https://github.com/YamYamVPN

---

## What Makes YamYam VPN Different?

| Feature | YamYam VPN |
|---|---|
| Android focused | ✅ |
| Free to use | ✅ |
| Account required | ❌ |
| Email required | ❌ |
| Phone number required | ❌ |
| Android 7.0+ | ✅ |
| One-tap connection | ✅ |
| Multiple connection modes | ✅ |
| VLESS-based connections | ✅ |
| Reality support | ✅ |
| XHTTP support | ✅ |
| Split tunneling | ✅ |
| DNS protection | ✅ |
| Public privacy policy | ✅ |
| APK verification information | ✅ |

---

## Core Features

### No Signup

YamYam VPN is designed to work without creating a user account.

You are not required to provide:

- Email address
- Phone number
- Username
- Password
- Account credentials

This reduces unnecessary registration steps and makes installation-to-connection faster.

### Android First

YamYam VPN is currently designed primarily for Android.

**Minimum supported version: Android 7.0+**

The Android-first approach allows the project to focus on mobile-specific VPN behavior, compatibility, routing, split tunneling, and network conditions.

### One-Tap Connectivity

The interface is designed to minimize unnecessary configuration.

Users can select an available connection mode and establish a VPN connection without manually configuring protocol parameters.

---

## Connection Technologies

YamYam VPN supports several modern technologies used in proxy and tunneling environments.

### VLESS

**VLESS** is a lightweight protocol commonly used with modern proxy infrastructures.

YamYam VPN uses VLESS-based connections in supported configurations.

### Reality

**Reality** can be used as part of supported connection configurations to provide an alternative method of establishing secure transport behavior.

Availability depends on the selected connection mode and server configuration.

### XHTTP

**XHTTP** is supported in compatible YamYam VPN connection configurations.

Transport availability may differ between servers, application versions, and network environments.

---

## Split Tunneling

YamYam VPN includes **Android split tunneling**.

Split tunneling lets users decide which applications should use the VPN connection and which applications should access the internet directly.

Example:

```text
Browser          → VPN
Messaging App    → VPN
Streaming App    → VPN
Banking App      → Direct Connection
Local Services   → Direct Connection
```

This gives users more control over application routing and can help avoid routing applications through the VPN when it is unnecessary.

---

## DNS Protection

DNS requests can reveal which domains a device attempts to access.

YamYam VPN includes DNS-related protection intended to keep supported DNS traffic within the appropriate VPN connection when applicable.

Privacy and data-handling details should always be verified against the latest official privacy policy:

**https://yamyamvpn.top/privacy/**

---

# Download YamYam VPN for Android

The official Android download page is:

## https://yamyamvpn.top/download/

Before installing an APK, users should confirm that the file was obtained from an official YamYam VPN source.

Avoid modified APKs, unofficial mirrors, or files distributed by unknown third parties.

---

## Verify Your APK

For direct APK distribution, file integrity matters.

Official YamYam VPN releases may include a **SHA-256 checksum** that can be used to verify that a downloaded APK has not changed.

A published release record should look similar to:

```text
Application: YamYam VPN
Platform: Android
Version: <VERSION>
File: YamYamVPN-<VERSION>.apk
SHA-256: <OFFICIAL_SHA256_CHECKSUM>
```

### Windows

```powershell
certutil -hashfile YamYamVPN.apk SHA256
```

### macOS

```bash
shasum -a 256 YamYamVPN.apk
```

### Linux

```bash
sha256sum YamYamVPN.apk
```

The generated SHA-256 value should exactly match the checksum published by YamYam VPN.

---

# Privacy & Transparency

VPN software processes network traffic, which makes transparency especially important.

YamYam VPN publishes information describing its privacy practices, data processing, third-party services, and related policies.

### Official documents

**Privacy Policy**  
https://yamyamvpn.top/privacy/

**Terms of Service**  
https://yamyamvpn.top/terms/

Users are encouraged to review these documents before using the service.

---

# Security

Security issues should be reported responsibly.

If you discover a vulnerability affecting YamYam VPN, please avoid publishing exploit details, credentials, private configuration information, server information, or sensitive user data in a public GitHub issue.

Use the official YamYam VPN contact channels available through:

https://yamyamvpn.top/

Responsible security research and vulnerability reports are appreciated.

---

# Repository Purpose

This repository exists as the official public GitHub resource for the Android version of **YamYam VPN**.

It may contain:

- Android release information
- APK verification data
- SHA-256 checksums
- Changelogs
- Technical documentation
- Security information
- Public issue tracking
- Installation information
- Troubleshooting information
- Public project resources

---

# Source Code Status

> **Important:** YamYam VPN is currently distributed as proprietary software.

The existence of this public GitHub repository does **not** mean the complete YamYam VPN application is open source.

Unless explicitly stated otherwise, this repository contains public documentation, release information, verification data, security information, and other project resources.

The complete Android application source code, backend infrastructure, server infrastructure, configuration systems, and internal services should not be assumed to be publicly available.

---

# Documentation

The YamYam VPN website publishes technical and educational information about VPNs, Android networking, privacy, and modern connection technologies.

Topics may include:

| Topic | Description |
|---|---|
| VLESS | Protocol concepts and use cases |
| Reality | Modern connection technology |
| XHTTP | Transport concepts |
| Split Tunneling | App-specific Android routing |
| DNS Protection | DNS privacy and VPN behavior |
| Android VPN | VPN concepts on Android |
| VPN Security | How to evaluate VPN applications |
| Privacy | Understanding VPN privacy practices |
| Troubleshooting | Common VPN connection issues |

### Read YamYam VPN Guides

https://yamyamvpn.top/blog/

---

# Frequently Asked Questions

<details>
<summary><strong>Is YamYam VPN free?</strong></summary>

Yes. YamYam VPN is available as a free Android VPN.

</details>

<details>
<summary><strong>Does YamYam VPN require an account?</strong></summary>

No. Users do not need to create an account before connecting.

</details>

<details>
<summary><strong>Do I need to provide an email address?</strong></summary>

No.

</details>

<details>
<summary><strong>Do I need to provide a phone number?</strong></summary>

No.

</details>

<details>
<summary><strong>Which platform does YamYam VPN support?</strong></summary>

YamYam VPN is currently focused on Android.

</details>

<details>
<summary><strong>What Android version is required?</strong></summary>

Android 7.0 or newer.

</details>

<details>
<summary><strong>Does YamYam VPN support VLESS?</strong></summary>

Yes. Supported connection modes can use VLESS-based configurations.

</details>

<details>
<summary><strong>Does YamYam VPN support Reality?</strong></summary>

Reality is supported in compatible connection configurations.

</details>

<details>
<summary><strong>Does YamYam VPN support XHTTP?</strong></summary>

XHTTP is supported where compatible with the selected connection configuration.

</details>

<details>
<summary><strong>Does YamYam VPN include split tunneling?</strong></summary>

Yes. Android split tunneling allows users to control which applications use the VPN connection.

</details>

<details>
<summary><strong>Is YamYam VPN open source?</strong></summary>

No. YamYam VPN is currently proprietary software unless a specific component is explicitly published under an open-source license.

</details>

---

# Official Resources

| Resource | Official Link |
|---|---|
| Website | https://yamyamvpn.top/ |
| Android Download | https://yamyamvpn.top/download/ |
| Privacy Policy | https://yamyamvpn.top/privacy/ |
| Terms of Service | https://yamyamvpn.top/terms/ |
| VPN Guides | https://yamyamvpn.top/blog/ |
| GitHub Organization | https://github.com/YamYamVPN |

---

# Brand & Authenticity

The official project name is:

**YamYam VPN**

Official domain:

**yamyamvpn.top**

Official GitHub organization:

**github.com/YamYamVPN**

Be cautious of websites, APK files, social profiles, or download pages impersonating YamYam VPN.

---

# Feedback & Issue Reports

Feedback from Android users is welcome.

Useful reports include:

- Connection reliability
- Connection speed
- Android compatibility
- Battery usage
- UI/UX problems
- Split tunneling issues
- DNS behavior
- Installation problems
- Documentation improvements

When reporting an issue, include your Android version and YamYam VPN version when possible.

Please do **not** include passwords, private configuration data, access credentials, or other sensitive information in public GitHub issues.

---

# Search & Discovery

YamYam VPN is designed for users looking for an:

- Free Android VPN
- Android VPN without signup
- VPN without email registration
- VPN without phone-number registration
- VLESS VPN for Android
- VPN with Reality support
- VPN with XHTTP support
- Android VPN with split tunneling
- Android VPN with DNS protection

These phrases describe real product capabilities and are included here to make the repository easier to understand for users, search engines, and AI-powered discovery systems.

---

# Project Status

YamYam VPN is actively evolving.

Features, protocols, servers, availability, download methods, and supported Android versions may change over time.

For the latest official information, always refer to:

**https://yamyamvpn.top/**

---

<div align="center">

## YamYam VPN

**Free Android VPN with no signup**

VLESS • Reality • XHTTP • Split Tunneling • DNS Protection

🌐 https://yamyamvpn.top/

⭐ Star this repository to follow future Android releases, documentation, verification information, and project updates.

</div>
