# 🎬 Radarr — Movie Collection Manager

### Automate Your Movie Library with Smart Management and Quality Upgrades

<p align="center">
  <strong>Discover · Organize · Manage · Upgrade</strong>
</p>

<p align="center">
  A powerful movie collection manager for organizing your digital library, monitoring releases, and automating movie imports.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Windows%20%7C%20Linux%20%7C%20macOS-blue" alt="Supported platforms">
  <img src="https://img.shields.io/badge/Category-Movie%20Management-purple" alt="Movie management">
  <img src="https://img.shields.io/badge/License-GPL--3.0-green" alt="GPL-3.0 License">
</p>

---

## 📖 Overview

**Radarr** is an open-source movie collection manager designed for users who want to organize and automate their personal movie libraries.

It integrates with supported download clients and indexers to search for movie releases, manage downloads, import completed files, organize movie folders, and upgrade existing files when a higher-quality version becomes available.

Whether you're building a home media server or maintaining a large movie collection, Radarr provides a centralized interface for managing your movies and their quality profiles.

**Official project:** https://github.com/Radarr/Radarr

---

## ✨ Key Features

| Feature | Description |
|---|---|
| 🎥 Movie Management | Add, track, and organize movies in one library. |
| 🔎 Release Search | Search for available releases through configured indexers. |
| ⚙️ Automation | Monitor feeds and automate supported download workflows. |
| 📂 Library Organization | Automatically import and organize completed downloads. |
| 🎞️ Quality Profiles | Configure preferred qualities and release requirements. |
| ⬆️ Quality Upgrades | Upgrade existing movie files when better releases match your settings. |
| 🔄 Download Integration | Connect compatible download clients, including supported BitTorrent and Usenet applications. |
| 🏷️ Metadata Management | Work with movie information, artwork, and library metadata. |
| 🔔 Media Server Integration | Integrate with supported media applications for notifications and library updates. |
| 🖥️ Cross-Platform Support | Available for Windows, Linux, macOS, and selected other platforms. |

---

## 🚀 Getting Started

### 1. Download Radarr

Get the latest stable release and installation instructions from the official project resources.

- **Official Website:** https://radarr.video/
- **GitHub Repository:** https://github.com/Radarr/Radarr
- **Installation Guide:** https://wiki.servarr.com/radarr/installation
- **Latest Releases:** https://github.com/Radarr/Radarr/releases

Always download software from trusted sources and review the installation instructions for your operating system.

### 2. Install and Launch

Choose the installation method appropriate for your environment.

Radarr supports several deployment options, including:

- Windows installation
- Linux installation
- macOS installation
- Manual installation for supported systems
- Third-party Docker images

**Note:** The Radarr team does not provide an official Docker image. If you choose Docker, review the official documentation and select a trusted third-party image.

### 3. Open the Web Interface

After installation and startup, open the Radarr web interface in your browser.

The default local address is:

`http://localhost:7878`

If Radarr is running on another machine, use the appropriate server address and configured port.

---

## ⚙️ Configuration

To get the most out of Radarr, configure the following components.

### Movie Library

Select your movie library folder and configure the root directories where movies should be organized.

### Indexers

Configure compatible indexers to discover available movie releases. Availability and setup requirements depend on the indexer and your environment.

### Download Clients

Connect a supported download client to allow Radarr to manage compatible download workflows.

### Quality Profiles

Choose the quality levels, formats, and release preferences that match your requirements.

### Media Management

Configure naming conventions, file organization, import behavior, and other library management settings.

### Integrations

Set up supported notifications and media-server integrations if you want your library updates reflected in other applications.

For detailed configuration instructions, consult the official Radarr documentation.

---

## 🧩 How Radarr Works

A typical Radarr workflow looks like this:

1. **Add a movie** to your collection.
2. **Configure your preferences** for quality and availability.
3. **Search for releases** using configured indexers and monitoring options.
4. **Manage downloads** through a compatible download client.
5. **Import completed files** into the appropriate movie library folder.
6. **Maintain your collection** with metadata, organization, and quality upgrades.

The exact workflow depends on your configuration, available indexers, download clients, and quality profiles.

---

## 💻 System Compatibility

Radarr supports multiple operating systems and deployment environments.

| Platform | Availability |
|---|---|
| Windows | Supported |
| Linux | Supported |
| macOS | Supported |
| Raspberry Pi and selected ARM systems | Depends on the supported build and architecture |
| Docker | Supported through third-party images |

Check the official installation guide for current requirements, supported architectures, and platform-specific instructions.

---

## 🛠️ Troubleshooting

### Radarr cannot connect to a download client

- Verify that the client is running.
- Check the hostname, port, credentials, and connection settings.
- Confirm that firewall rules permit the connection.

### Downloaded movies are not imported

- Check the download client's reported file path.
- Verify that Radarr has permission to access the download and library folders.
- Review remote path mappings if the applications use different paths.
- Check the application logs for import errors.

### Movies are not appearing in search results

- Verify the indexer configuration.
- Check the movie's monitoring settings.
- Review quality profiles and release restrictions.
- Confirm that the configured indexers are available and working.

### Radarr cannot access the movie library

- Check folder permissions.
- Verify the configured root folder.
- Confirm that the library path exists and is accessible to the Radarr process.

For further assistance, consult the official documentation and support resources.

---

## 🔐 Security Recommendations

- Download Radarr from official project resources.
- Keep Radarr and its dependencies updated.
- Use strong credentials where authentication is available.
- Avoid exposing the web interface directly to the public internet without appropriate security controls.
- Restrict access to trusted users and networks.
- Back up your configuration and database before major changes.

---

## ❓ Frequently Asked Questions

### What is Radarr?

Radarr is an open-source movie collection manager that automates supported movie search, download management, file importing, organization, and quality upgrades.

### Is Radarr available for Windows?

Yes. Radarr provides Windows installation options. Consult the official installation guide for the appropriate package.

### Does Radarr support Linux and macOS?

Yes. Radarr offers installation options for supported Linux distributions and macOS systems.

### Can Radarr automatically organize movie files?

Yes. When configured correctly, Radarr can import completed downloads and organize them according to your library and media management settings.

### Can Radarr upgrade movie quality?

Yes. You can configure quality profiles and upgrade preferences so Radarr can seek better-quality releases when matching releases become available.

### Does Radarr require a download client?

For automated download workflows, Radarr generally needs a compatible download client and appropriately configured indexers.

### Where can I find official documentation?

Visit the official project repository and the Radarr installation and documentation resources listed above.

---

## 🔗 Official Resources

- **Website:** https://radarr.video/
- **GitHub Repository:** https://github.com/Radarr/Radarr
- **Releases:** https://github.com/Radarr/Radarr/releases
- **Installation Guide:** https://wiki.servarr.com/radarr/installation
- **Support:** https://radarr.video/support

---

## 🔎 Search Keywords

Radarr, Radarr movie manager, Radarr movie collection manager, movie library management, automated movie organization, movie download management, media server software, movie quality upgrades, Radarr Windows, Radarr Linux, Radarr macOS, open-source movie management software, personal media library, movie metadata management, Radarr installation guide.

---

## 📜 License

Radarr is distributed under the **GNU General Public License v3.0 (GPL-3.0)**. Refer to the official repository for the license text and project details.

---

<p align="center">
  <strong>Radarr — A Smarter Way to Manage Your Movie Collection 🎬</strong>
</p>
