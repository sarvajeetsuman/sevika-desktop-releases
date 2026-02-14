# Sevika Medical Store Desktop v1.0.1

**Release Date:** February 14, 2026  
**Type:** Security & Maintenance Update

## 🔒 Security Enhancements

This release focuses on hardening the security of the desktop application for production deployments.

### What's New

#### 1. **Production DevTools Disabled**
- Developer tools are now completely disabled in production builds
- Users cannot inspect application code or network requests
- Enhanced protection of sensitive data and API endpoints
- DevTools remain available in development mode for debugging

#### 2. **Keyboard Shortcuts Blocked**
- F12 (Open DevTools) - Blocked
- Ctrl+Shift+I (Open DevTools) - Blocked  
- Ctrl+Shift+J (Open Console) - Blocked
- Cmd+Option+I (Mac DevTools) - Blocked
- Cmd+Option+J (Mac Console) - Blocked

#### 3. **Version Display Updated**
- Login and signup screens now correctly show version 1.0.1
- Consistent branding across all authentication screens

## 📥 Download

Choose the appropriate installer for your needs:

### NSIS Installer (Recommended)
**File:** `Sevika-Medical-Store-Setup-1.0.1.exe`  
**Size:** 73.09 MB  
**Features:**
- Full installation with Start Menu and Desktop shortcuts
- Installation directory selection
- Automatic updates (future)
- Clean uninstall support

### Portable Version
**File:** `Sevika-Medical-Store-Portable-1.0.1.exe`  
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

## 🔄 Upgrading from v1.0.0

If you have v1.0.0 installed:

1. **Installer Version:** Simply run the v1.0.1 installer - it will upgrade automatically
2. **Portable Version:** Download v1.0.1 and replace your existing .exe file
3. Your data and settings will be preserved

## ✅ What's Unchanged

All features from v1.0.0 remain fully functional:
- ✅ Patient management
- ✅ Prescription tracking
- ✅ Inventory management
- ✅ Sales and billing with GST
- ✅ HSN code support (326+ codes)
- ✅ Bonus quantity tracking
- ✅ Staff management
- ✅ Multi-language support
- ✅ Lab test recommendations
- ✅ Admin dashboard

## 📋 Technical Changes

### Files Modified
- `electron/main.js` - DevTools and keyboard handling
- `src/screens/LoginScreen.tsx` - Version display
- `src/screens/SignupScreen.tsx` - Version display

### Build Information
- **Electron:** 28.0.0
- **React:** 18.2.0
- **Build Tool:** Vite 5.0.8
- **Build Date:** February 14, 2026, 22:30 IST

## 🐛 Known Issues

None reported in this release.

## 📞 Support

- **Issues:** [GitHub Issues](https://github.com/sarvajeetsuman/sevika-desktop-releases/issues)
- **Website:** [sevika.online](https://sevika.online)
- **Email:** support@sevika.online

## 📝 Checksums

For security verification:

```
Sevika-Medical-Store-Setup-1.0.1.exe
Size: 76,641,005 bytes (73.09 MB)

Sevika-Medical-Store-Portable-1.0.1.exe
Size: 76,399,349 bytes (72.86 MB)
```

## 🎉 Thank You

Thank you for using Sevika Medical Store Desktop! This security update ensures your pharmacy data remains protected while maintaining all the features you rely on.

---

**Previous Version:** [v1.0.0](RELEASE_NOTES_v1.0.0.md)  
**Full Changelog:** [CHANGELOG.md](CHANGELOG.md)
