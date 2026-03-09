# Sevika Medical Store Desktop v1.0.3

**Release Date:** March 10, 2026  
**Type:** Feature & Fixes Release

## 🚀 Feature & Fixes Release

Major POS improvements, supplier enhancements, and inventory accuracy fixes for Sevika Medical Store Desktop Application.

## ✨ New Features

### 1. **Multi-Bill POS (Parallel Customer Billing)**
- Handle up to **5 customer bills simultaneously** without losing cart state
- Tabbed bill interface — click to switch between bills instantly
- Each bill tab shows the running total and customer name at a glance
- Open new bills with the **＋ New Bill** button; close any bill with the × button
- Bill sessions persist across screen navigation within the same login session
- All bills are cleared automatically on logout

### 2. **Supplier Drug License**
- Add and store a **Drug License Number** for each supplier in the Supplier Detail screen
- Displayed alongside existing supplier information for quick reference during purchase orders

### 3. **Edit & Delete Orders**
- Edit existing purchase orders directly from the Receive Order screen
- Delete orders that are no longer needed
- Actions available inline — no need to navigate away

### 4. **POS Catalogue Fallback**
- When a medicine is **not found in inventory**, POS now automatically searches the Medicine Master catalogue
- Results are shown with an **"Out of Stock ⚠️"** label so staff can identify what needs restocking
- Helps cashiers inform customers and speed up reorder decisions

## 🔧 Fixes

### **Inventory Stock Quantity**
- Stock quantity in inventory now correctly reflects **real available stock** instead of always showing total purchased quantity
- Prevents overbilling and stock discrepancy issues

### **Order Bill & Total Calculations**
- Fixed calculation errors in received order bills and totals
- Accurate invoicing is now reflected when receiving purchase orders

### **GST Default — Off**
- GST is now **disabled by default** in POS; can be toggled on per transaction
- Reduces friction for non-GST sales and avoids accidental GST charges

## 💳 Subscription

### **Razorpay Payment Subscription Renewal**
- Subscription renewal is now available directly from **Settings → Subscription**
- Integrated Razorpay payment flow for seamless plan renewal within the app

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
- ✅ Medicine Type Filter in Medicine Master
- ✅ Bonus Scheme proportional calculation in POS and Receive Order
- ✅ Combined filters (Status + Type) in quick and advanced search
- ✅ DevTools disabled in production builds
- ✅ Complete pharmacy management system
- ✅ Patient & prescription tracking
- ✅ Sales & billing with GST support
- ✅ Staff management with role-based access

## 🐛 Known Issues

None at this time.
