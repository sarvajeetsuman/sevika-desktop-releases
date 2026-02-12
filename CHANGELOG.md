# Changelog

All notable changes to Sevika Medical Store Desktop App will be documented in this file.

## [1.0.0] - 2026-02-12

### Added
- Initial release of Sevika Medical Store Desktop Application
- Complete pharmacy management system with desktop interface
- Multi-language support (English, Hindi, Marathi)
- Patient management with detailed profiles
- Prescription management and medication tracking
- Inventory management for medicines and items
- Sales and billing with GST support
- HSN code support for pharmaceutical products (326+ codes)
- Bonus quantity tracking for pharmacy purchases
- Lab test recommendations and tracking
- Staff management and role-based access
- Admin dashboard with analytics
- Offline-first architecture with API sync
- Secure credential storage
- Auto-update support (future)

### Security
- DevTools disabled in production build
- Keyboard shortcuts for DevTools blocked (F12, Ctrl+Shift+I, etc.)
- Secure API authentication with token management
- Context isolation enabled
- Node integration disabled for security

### Technical
- Built with Electron 28.0.0
- React 18.2.0 for UI
- Vite for fast builds
- TypeScript support
- Windows x64 support
- NSIS installer and portable versions

### Fixed
- High DPI display scaling issues on Windows
- API CORS configuration for local development
- Session persistence and token refresh
- Menu navigation and routing

---

## Release Notes

### Installation Types

**Installer (Recommended)**
- `Sevika-Medical-Store-Setup-1.0.0.exe` - Full installer with Start Menu and Desktop shortcuts
- Installation directory selection
- Automatic updates (future releases)
- ~150 MB download

**Portable Version**
- `Sevika-Medical-Store-Portable-1.0.0.exe` - No installation required
- Run directly from any folder
- Perfect for USB drives or temporary usage
- ~145 MB download

### System Requirements
- Windows 10 or later (x64)
- 4 GB RAM (8 GB recommended)
- 500 MB free disk space
- Internet connection for API access

### First Time Setup
1. Download and install/run the application
2. Enter your API endpoint (default: http://35.207.208.132)
3. Login with your credentials
4. Start managing your pharmacy!

### Support
- Issues: https://github.com/sarvajeetsuman/sevika-desktop/issues
- Website: https://sevika.online
- Email: support@sevika.online
