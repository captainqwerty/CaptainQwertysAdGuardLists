<div id="top"></div>

<div align="center">

<h1><b>CaptainQwerty's AdGuard Home Lists</b></h1>

<p>
  <strong>Curated whitelist and blocklist for AdGuard Home DNS filtering</strong>
</p>
<p>
  <em>Keep your essential services working while blocking unwanted content</em>
</p>

[![Repository](https://img.shields.io/badge/GitHub-Repository-blue?logo=github)](https://github.com/captainqwerty/CaptainQwertysAdGuardLists) [![Stars](https://img.shields.io/github/stars/captainqwerty/CaptainQwertysAdGuardLists?style=flat-square&logo=github)](https://github.com/captainqwerty/CaptainQwertysAdGuardLists/stargazers) [![Forks](https://img.shields.io/github/forks/captainqwerty/CaptainQwertysAdGuardLists?style=flat-square&logo=github)](https://github.com/captainqwerty/CaptainQwertysAdGuardLists/network/members) [![License](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT) [![Last Updated](https://img.shields.io/badge/Last%20Updated-April%202026-orange)](https://github.com/captainqwerty/CaptainQwertysAdGuardLists)

</div>

---

## 📋 Table of Contents

- [About The Project](#about-the-project)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [File Structure](#file-structure)
- [Categories](#categories)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgments](#acknowledgments)

---

## 🎯 About The Project

This repository contains carefully curated DNS filter lists for [AdGuard Home](https://adguard.com/en/adguard-home/overview.html), designed to balance privacy protection with functionality. The lists prevent blocking of essential services while allowing you to maintain control over unwanted content.

**Disclaimer:** I am too lazy to not have used a template for this ReadMe and AI to write most of it.

---

## ✨ Features

- **🛡️ Comprehensive Coverage**: Supports major streaming platforms, social media, cloud services, and gaming
- **📱 UK Services**: Special attention to UK-based services and regional content
- **📚 Documented**: Clear organisation and detailed comments

<p align="right">(<a href="#top">Back to top</a>)</p>

---

## 🚀 Installation

### Prerequisites

- [AdGuard Home](https://adguard.com/en/adguard-home/overview.html) installed and running
- Access to your AdGuard Home admin interface

### Quick Setup

1. **Access your AdGuard Home dashboard**
2. **Navigate to Settings → DNS Settings**
3. **Import the lists using the URLs below**

<p align="right">(<a href="#top">Back to top</a>)</p>

---

## 📖 Usage

### Allowlist

Import this list to prevent blocking of essential services:

```
https://raw.githubusercontent.com/captainqwerty/CaptainQwertysAdGuardLists/main/Allowlist.txt
```

**Location**: Settings → DNS Settings → DNS allowlist

**Purpose**: Allows essential domains that might otherwise be blocked by general filter lists

### Blocklist

Import this list to block unwanted services:

```
https://raw.githubusercontent.com/captainqwerty/CaptainQwertysAdGuardLists/main/Blocklist.txt
```

**Location**: Settings → DNS Settings → DNS blocklist

**Purpose**: Blocks specific unwanted services (currently focused on Android TV restrictions)

### Understanding Rule Priority

- Rules with `^$important` have the highest priority
- `^$important` rules cannot be overridden by other lists
- Regular rules can be overridden by higher-priority lists

<p align="right">(<a href="#top">Back to top</a>)</p>

---

## 📁 File Structure

```
CaptainQwertysAdGuardLists/
├── README.md                # This file
├── Allowlist.txt            # Domains to allow
└── Blocklist.txt            # Domains to block
```

<p align="right">(<a href="#top">Back to top</a>)</p>

---

## 🏷️ Categories

### Allowlist Categories

- **Infrastructure & Security**: DNS, certificates, security services
- **Streaming & Video**: YouTube, Netflix, Disney+, Plex, media databases
- **Social Media & Communication**: Instagram, WhatsApp, Twitter, Reddit, Facebook
- **Google & Cloud Services**: Core Google services, APIs, cloud infrastructure
- **Development & CDN**: GitHub, Cloudflare, content delivery networks
- **Microsoft & Office**: Office 365, Windows, Xbox, Skype
- **Storage & Backup**: Amazon AWS, Dropbox, cloud storage
- **Entertainment & Media**: Wikipedia, TED, media services
- **Consumer Services**: Apple, banking, shopping services
- **Gaming & Entertainment Platforms**: Gaming services and platforms

### Blocklist Categories

- **Android TV Restrictions**: Blocks Android TV-specific tracking and unwanted services

<p align="right">(<a href="#top">Back to top</a>)</p>

---

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

### Adding Domains

1. **Fork the repository**
2. **Add domains to the appropriate category** in the relevant file
3. **Follow the existing formatting** and commenting style
4. **Test your changes** to ensure they work as expected
5. **Update the "Last Updated" date** in file headers
6. **Submit a pull request** with a clear description

### Guidelines

- **Categorise properly**: Add domains to the most appropriate category
- **Use comments**: Explain why each domain is included
- **Test thoroughly**: Ensure changes don't break existing functionality
- **Keep it UK-focused**: Prioritise services popular in the UK
- **Regular updates**: Help maintain the lists as services change

### Reporting Issues

Found a domain that should be allowed/blocked? [Open an issue](https://github.com/captainqwerty/CaptainQwertysAdGuardLists/issues) with:
- The domain in question
- Why it should be allowed/blocked
- Which service it belongs to
- Any relevant context

<p align="right">(<a href="#top">Back to top</a>)</p>

---

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.

<p align="right">(<a href="#top">Back to top</a>)</p>

---

## 🙏 Acknowledgments

- [AdGuard Home](https://adguard.com/en/adguard-home/overview.html) - The DNS filtering platform
- [Othneildrew's Best-README-Template](https://github.com/othneildrew/Best-README-Template) - README template inspiration
- The open-source community for inspiration and tools

<p align="right">(<a href="#top">Back to top</a>)</p>

---

<div align="center">

[⬆ Back to top](#top)

</div>