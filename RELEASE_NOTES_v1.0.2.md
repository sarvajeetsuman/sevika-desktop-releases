# Sevika Medical Store Desktop v1.0.2

**Release Date:** February 25, 2026  
**Type:** Feature & Security Release

## 🚀 Feature & Security Release

New features and production security hardening for Sevika Medical Store Desktop Application.

## ✨ New Features

### 1. **Medicine Type Filter**
- New "Type" filter bar on the Medicine Master screen — filter by TABLET, CAPSULE, SYRUP, INJECTION, and more with one click
- Type filter works across all modes: browsing, quick search, and advanced search
- Loaded dynamically from the server — always reflects the types available in your database

### 2. **Combined Filters in Search**
- Quick search now correctly applies Status (Approved/Pending) and Type filters simultaneously
- Advanced search unified with Status + Type filters in a single request — no more lost filters when switching modes

## 🔧 Improvements

### **Bonus Scheme — Proportional Calculation**
- Bonus quantity is now calculated proportionally instead of requiring complete sets
- Example: scheme `9+1` on qty `4` → `0.4` free, `3.6` paid (previously gave `0` free)
- Example: scheme `1+1` on qty `25` → `12.5` free, `12.5` paid
- Example: scheme `10+8` on qty `50` → `22.22` free, `27.78` paid
- Applies consistently in both POS and Receive Order screens
- Added validation: both parts of a bonus scheme must be greater than 0

## 🛡️ Security Enhancements

- **DevTools fully disabled in production builds** — Enhanced protection against code inspection
- **Keyboard shortcuts blocked** — F12, Ctrl+Shift+I, Ctrl+Shift+J, and all developer tool shortcuts
- DevTools remain available in development mode for debugging

## 📥 Download

Choose the appropriate installer for your needs:

### NSIS Installer (Recommended)
**File:** `Sevika-Medical-Store-Setup-1.0.2.exe`  
**Size:** 73.09 MB  
**Features:**
- Full installation with Start Menu and Desktop shortcuts
- Installation directory selection
- Clean uninstall support

### Portable Version
**File:** `Sevika-Medical-Store-Portable-1.0.2.exe`  
**Size:** 72.86 MB  
**Features:**
- No installation required
- Run directly from any folder
- Perfect for USB drives
- Leave no traces on system

## ⚙️ System Requirements

- **OS:** Windows 10 or later (64-bit)
- **RAM:** 4 GB minimum, 8 GB recommended
- **Storage:** 500 MB free disk space
- **Network:** Internet connection for API access

## 🔄 Upgrading from v1.0.1

Simply run the new installer — it will upgrade automatically while preserving your data and settings.

## ✅ What's Unchanged

All features from v1.0.1 remain fully functional:
- ✅ Complete pharmacy management system
- ✅ Patient & prescription tracking
- ✅ Inventory management with HSN codes
- ✅ Sales & billing with GST support
- ✅ Staff management with role-based access
- ✅ Admin dashboard with analytics

## 🐛 Known Issues

None reported in this release.

## 📞 Support

- **Issues:** [GitHub Issues](https://github.com/sarvajeetsuman/sevika-desktop-releases/issues)
- **Website:** [sevika.online](https://sevika.online)
- **Email:** support@sevika.online

---

**Previous Version:** [v1.0.1](RELEASE_NOTES_v1.0.1.md)  
**Full Changelog:** [CHANGELOG.md](CHANGELOG.md)
