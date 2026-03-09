# Sevika Medical Store Desktop v1.0.3

**Release Date:** March 10, 2026  
**Type:** Feature & Fixes Release

## 🚀 Supplier & POS Overhaul Release

Major improvements to the Supplier module, Point of Sale, and inventory accuracy.

## ✨ New Features

### 1. **Multi-Bill POS — Serve Multiple Customers at Once**
- POS now supports up to **5 simultaneous bills** — serve multiple customers without losing any cart
- A bill tab bar above the search shows each bill with item count and running total
- Switch between bills instantly; each bill has its own cart, customer, and payment method
- Switching to another screen (e.g. Inventory) and coming back no longer clears the active bill
- All bills are cleared automatically on logout and app restart

### 2. **Supplier Drug License Number**
- Drug License Number field added to the Add Supplier form
- Stored and displayed on the Supplier detail screen for quick reference during purchase orders

### 3. **Edit & Delete Order Bills**
- Edit button on each order bill to update the bill number, date, and notes
- Delete button with safety checks — blocked if any payment has been made or stock has already been sold
- The delete option only appears when it is actually safe to remove the order
- Deleting an order automatically reverses any stock that was added from it

### 4. **Medicine Not Found in POS — Catalogue Hint**
- When a medicine has no stock in inventory, POS automatically searches the medicine catalogue
- Shows a ⚠️ hint — *"Not available in stock — found in medicine catalogue"* — so staff know the medicine exists but hasn't been received yet

## 🔧 Improvements & Fixes

### **Manufacturer Visible in Order Bill**
- Manufacturer name is now a dedicated column in the order items table

### **Inventory Stock Correctly Shown After a Sale**
- Fixed a bug where stock quantity was not updating after a sale was made
- Stock levels now always reflect the actual quantity available for sale

### **Order Bill — Accurate Pricing**
- Prices in order bills now show correctly with 2 decimal places (e.g. ₹12.50 instead of ₹13)

### **Order Bill — Correct Item Count**
- The item count in the order bill header now shows the correct number of items instead of 0

### **Order Bill — Accurate Payment Status**
- Order status now correctly shows PENDING, PARTIAL, or PAID based on actual payments recorded

### **GST Off by Default in POS**
- GST toggle in POS now defaults to OFF — appropriate for retail (OTC) sales
- Can still be enabled manually per bill when needed

### **Receive Order — Add Item Button Repositioned**
- Add Item button moved to a more convenient location for faster multi-item entry during wholesale receiving

### **In-App Subscription Renewal**
- Subscription can now be renewed directly from Settings → Subscription without leaving the app

## 📥 Download

Choose the appropriate installer for your needs:

### NSIS Installer (Recommended)
**File:** `Sevika-Medical-Store-Setup-1.0.3.exe`  
**Features:**
- Full installation with Start Menu and Desktop shortcuts
- Installation directory selection
- Clean uninstall support

### Portable Version
**File:** `Sevika-Medical-Store-Portable-1.0.3.exe`  
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

## 🔄 Upgrading from v1.0.2

Simply run the new installer — it will upgrade automatically while preserving your data and settings.

## ✅ What's Unchanged

All features from v1.0.2 remain fully functional:
- ✅ Medicine type filters and combined search filters
- ✅ Proportional bonus scheme calculations
- ✅ Complete pharmacy management system
- ✅ Patient & prescription tracking
- ✅ Inventory management with HSN codes
- ✅ Sales & billing with GST support
- ✅ Staff management with role-based access
- ✅ Admin dashboard with analytics

## 🐛 Known Issues

- SGST/CGST split billing (planned for v1.0.4)

## 📞 Support

- **Issues:** [GitHub Issues](https://github.com/sarvajeetsuman/sevika-desktop-releases/issues)
- **Website:** [sevika.online](https://sevika.online)
- **Email:** support@sevika.online
- **Previous Version:** v1.0.2 — [Release Notes](RELEASE_NOTES_v1.0.2.md)
- **Full Changelog:** [CHANGELOG.md](CHANGELOG.md)
