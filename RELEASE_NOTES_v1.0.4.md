# Sevika Medical Store Desktop v1.0.4

**Release Date:** March 24, 2026  
**Type:** Feature & Fixes Release

## 🚀 GST Compliance & Wholesale Upgrade

Major additions for GST reporting, enhanced supplier returns, and a dedicated wholesale POS — alongside critical inventory and bug fixes.

## ✨ New Features

### 1. **GSTR-1 Report**
- Generate GSTR-1 (Outward Supplies) directly from the app
- Covers B2B and B2C sales with HSN/SAC summary
- Export-ready format for filing with your CA or GST portal

### 2. **GSTR-2 Report**
- Generate GSTR-2 (Inward Supplies / Purchase Register) from received purchase orders
- Tracks ITC (Input Tax Credit) eligibility across all supplier invoices
- Reconcile purchases quickly before filing

### 3. **Segregated Wholesale POS**
- Wholesale billing is now a completely separate POS mode from retail
- Wholesale POS applies trade discounts, bulk pricing, and GST-inclusive invoicing by default
- Switch between Retail and Wholesale POS from the sidebar without cart conflict
- Each mode maintains its own bill sessions independently

### 4. **Enhanced Supplier Return**
- Supplier Return module rebuilt with per-batch return support
- Return specific batch numbers and quantities from any past purchase order
- Credit note generated automatically on return confirmation
- Inventory is adjusted in real-time on return submission

## 🔧 Improvements & Fixes

### **Inventory Accuracy Fixes**
- Fixed incorrectly reported stock quantities after partial sales and supplier returns
- Batch-level inventory now correctly deducted on FIFO basis across all transactions
- Stock levels refresh immediately after a sale, return, or adjustment — no manual reload needed

### **Bug Fixes**
- Fixed crash when opening Supplier Return screen with no prior purchase orders
- Fixed GST calculation rounding error on multi-item bills with mixed tax slabs
- Fixed duplicate entry appearing in order bills after a quick re-scan
- Fixed supplier name not appearing in return confirmation dialog
- Various UI alignment and loading-state fixes across the app
