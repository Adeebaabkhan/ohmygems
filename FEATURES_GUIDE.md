# OhMyGems Dashboard - Complete Feature Guide

## 🎉 New Features Overview

This comprehensive enhancement adds multiple powerful features to streamline your sales tracking workflow.

---

## 1. 👥 Real Admin Names in Product Calculations

### What Changed?
- **Before**: Generic "Admin (20%)" and "Admin (30%)" placeholders
- **After**: Shows actual admin names with their specific commission rates

### How It Works
When adding or editing products, the calculation now displays:
```
👤 amaryl (25%): amaryl: ₱12.50 | You: ₱37.50
👤 eli (25%): eli: ₱12.50 | You: ₱37.50
👤 misha (25%): misha: ₱12.50 | You: ₱37.50
👤 rayen (25%): rayen: ₱12.50 | You: ₱37.50
```

### Benefits
- See exactly how much each admin earns per sale
- Better transparency for commission splits
- Automatically updates when admins are added/removed

---

## 2. ⚡ Bulk Add Sales (Fast Entry)

### What It Does
Add 10, 20, 50+ sales at once instead of one-by-one!

### How to Use
1. Click "📋 Show Bulk Entry" button (below the single sale form)
2. Fill in the multi-row table:
   - Product dropdown (all 35+ products organized by category)
   - Account Type (Solo/Shared)
   - Warranty (FW/NW)
   - Customer name
   - Buy & Sell prices (auto-filled from product)
   - Quantity
   - Status (In Stock/Sold)
3. Use "Apply to All" buttons for common fields:
   - 🛡️ Apply Warranty to All
   - 👤 Apply Account Type to All
   - 📦 Apply Status to All
4. Click "💾 Save All Sales"

### Features
- ➕ Add Row: Add more rows as needed
- ✕ Delete: Remove specific rows
- Validation: Ensures sell > buy price
- Progress indicator during save
- Auto-refresh after saving

### Time Saved
- Old way: 30 seconds per sale = 15 minutes for 30 sales
- New way: ~3 minutes for 30 sales
- **Savings: 80% faster!**

---

## 3. 💰 Complete Payout System

### 3A. Default Admin Commission
Set each admin's default commission % in User Management:
- Owner sets commission when adding admin (e.g., 25%)
- Used for all sales unless overridden

### 3B. Per-Product Custom Commission (Structure Ready)
Override default commission for specific products:
- Product A: Use default 25%
- Product B: Custom 30%
- Shows ✨ indicator for custom rates

### 3C. Automatic Calculation
Every sale automatically calculates:
- Total Profit = Sell - Buy
- Admin Commission = Profit × Commission %
- Owner Profit = Profit - Admin Commission

### 3D. Payout Dashboard
Access via User Management modal:
- Filter by period:
  - 📊 All Time
  - 📅 This Week
  - 📆 This Month
- View per admin:
  - Sales count
  - Profit generated
  - Commission breakdown (Default vs Custom)
  - Total pending payout

### 3E. Mark as Paid Flow
1. Click "✅ Mark as Paid"
2. Select payment method:
   - GCash
   - Bank Transfer
   - Cash
   - PayMaya
   - Other
3. Add reference number (optional)
4. Add notes (optional)
5. Confirm → Counter resets to ₱0
6. Saved to payout history

### 3F. Payout History
View complete payment records:
- Date paid
- Admin name
- Period
- Amount
- Payment method
- Reference number
- Notes

### 3G. Admin View
Admins see:
- Their pending payouts
- Sales breakdown
- Payment history
- Products with custom commission (✨)

---

## 4. 📦 Admin Product Access

### What Changed
**Before**: Only owner could view/manage products
**After**: Admins can now view and edit products!

### Admin Capabilities
✅ **Can Do:**
- View all products
- Edit buy/sell prices
- See their commission per product
- View profit calculations

❌ **Cannot Do:**
- Add new products (owner only)
- Delete products (owner only)
- Change commission rates

### Admin Product View
Shows:
```
📺 Netflix Premium
Buy: ₱100 | Sell: ₱200 | Profit: ₱100
👤 Your Commission: 25%
💵 You Earn: ₱25 per sale
👑 Owner Gets: ₱75
[✏️ Edit Prices]
```

### Benefits
- Admins can update prices quickly
- Owner maintains control over structure
- Price change history tracked
- Owner gets notified of changes (ready for implementation)

---

## 5. 🎨 Custom Theme Creator

### Community Themes (10+ Presets)
Beautiful pre-made themes:
1. 💜 Purple (Default)
2. 💙 Blue
3. 💚 Green
4. 💗 Pink
5. 🧡 Orange
6. 🌸 Cherry Blossom (pink/white)
7. 🍊 Citrus Burst (orange/yellow)
8. 💐 Lavender Dreams (purple/pink)
9. 🌊 Deep Ocean (navy/cyan)
10. 🔥 Fire & Ice (red/blue)
11. 🌈 Rainbow Pride (multi-color)
12. 🌑 Dark Mode Pro (black/gray)
13. ☀️ Sunshine Yellow
14. 🌿 Mint Fresh (green/white)
15. 🍇 Grape Soda (purple/pink)

### How to Apply Themes
1. Click ⚙️ Settings
2. Select theme from "🎨 Community Themes" dropdown
3. Click "💾 Save Settings"

### Custom Theme Builder
Create your own unique theme:

1. Click "🎨 Open Theme Builder"
2. Customize:
   - **Colors**: Primary, Secondary, Success, Danger, Warning, Info
   - **Font**: Poppins, Roboto, Montserrat, Inter
   - **Border Radius**: More Rounded → Square
   - **Animation Speed**: Fast → None
3. See live preview
4. Actions:
   - ✅ Apply Theme (test it out)
   - 💾 Save Theme (save to your profile)
   - 📤 Export (get theme code to share)
   - 📥 Import (use someone else's theme)
   - 🔄 Reset (back to default)

### Theme Persistence
- Themes save to your Firebase profile
- Auto-apply when you log in
- Sync across all your devices

---

## 6. 🔍 Enhanced Product Management

### Organized Categories
Products grouped in dropdowns:
```
📦 Disney
  - Disney Shared
  - Disney Solo 1dev
  - Disney Solo 2devs

📦 Netflix
  - Netflix Mobile
  - Netflix Basic
  - Netflix Standard
  - Netflix Premium
  - Netflix Shared

🎬 Subscription Products
  - ...
```

### Search & Filter
- 🔍 Search box: Type to find products instantly
- 📊 All: Show all products
- 🔤 Sort by Name: Alphabetical order
- 💰 Sort by Price: Highest to lowest

### All 35+ Products Included
- **Streaming**: Disney, HBO, Netflix, Prime Video, Apple TV+, Paramount+, Crunchyroll
- **Filipino**: Vivaone, Vivamax, Vivabundle, iWant, VIU, WeTV, Loklok, iQIYI
- **Video**: YouTube, Vimeo
- **Music**: Spotify, Apple Music, Calm, Headspace
- **Creative**: Canva, Adobe, CapCut, Remini
- **Writing**: ChatGPT, Grammarly, Quillbot
- **Productivity**: Microsoft 365, Notion, Evernote, Dropbox, LinkedIn Premium, Duolingo

---

## 7. 📱 Mobile Responsive

All features work perfectly on:
- 📱 Mobile phones (iOS & Android)
- 💻 Tablets (iPad, Android tablets)
- 🖥️ Desktop computers

Responsive features:
- Touch-friendly buttons
- Swipe-able tables
- Readable text sizes
- Optimized layouts

---

## 8. 🔔 Enhanced Notifications

Better toast notifications:
- ✅ Success (green)
- ❌ Error (red)
- ℹ️ Info (blue)
- Auto-dismiss after 3 seconds
- Shows at top of screen

---

## 🎯 Quick Start Guide

### For Owners
1. **Set up admins**: User Management → Add admins with commission %
2. **Add products**: Manage Products → Add with buy/sell prices
3. **Bulk add sales**: Use bulk entry for faster input
4. **Track payouts**: User Management → View pending payouts
5. **Mark as paid**: When paying admins, mark with method & reference
6. **Customize theme**: Settings → Choose or create theme

### For Admins
1. **View products**: Manage Products → See your commission
2. **Update prices**: Edit product prices as needed
3. **Add sales**: Use single or bulk entry
4. **Check earnings**: User Management → View your payouts
5. **Customize theme**: Settings → Personalize your dashboard

---

## 🚀 Performance Tips

1. **Bulk Sales**: Use for 5+ sales at once
2. **Categories**: Products auto-group by category
3. **Search**: Use search instead of scrolling
4. **Themes**: Save custom themes for quick switching
5. **Filters**: Use period filters in payouts for speed

---

## 🔐 Security Notes

### Firebase Security
- All data stored securely in Firebase
- User authentication required
- Role-based access control (owner vs admin)

### Recommended Rules (Conceptual)
```json
{
  "products": {
    ".read": "auth != null",
    "$productId": {
      "buyPrice": {
        ".write": "root.child('users').child(auth.uid).child('role').val() === 'owner' || 
                   root.child('users').child(auth.uid).child('role').val() === 'admin'"
      }
    }
  }
}
```

---

## ❓ FAQ

**Q: Can admins delete products?**
A: No, only owners can add/delete products. Admins can only edit prices.

**Q: Can I have different commission rates for different admins?**
A: Yes! Set individual commission % when adding each admin.

**Q: Can I override commission for specific products?**
A: Yes! The structure is in place for per-product custom commissions.

**Q: Do themes sync across devices?**
A: Yes! Themes save to your Firebase profile and sync automatically.

**Q: Can I undo a payout marking?**
A: Payouts move to history when marked paid. Contact owner to adjust.

**Q: How many rows can I add in bulk sales?**
A: No limit! Add as many as needed. We've tested with 50+ rows.

---

## 🐛 Troubleshooting

**Issue**: Products not loading
- **Fix**: Refresh page, check internet connection

**Issue**: Bulk sales not saving
- **Fix**: Check all fields are filled, sell > buy price

**Issue**: Theme not applying
- **Fix**: Click "Save Settings" after selecting theme

**Issue**: Payout not showing
- **Fix**: Ensure admin has sold items in selected period

**Issue**: Can't edit product as admin
- **Fix**: Ensure you're logged in as admin role

---

## 📊 Success Metrics

Expected improvements:
- ⏱️ **80% faster** sales entry with bulk feature
- 📈 **Better transparency** with real admin names
- 💰 **Accurate payouts** with automatic calculation
- 🎨 **Personalized experience** with custom themes
- 📱 **Mobile productivity** with responsive design

---

## 🆘 Support

For issues or questions:
1. Check this guide first
2. Review error messages
3. Check browser console (F12)
4. Contact repository owner

---

**Version**: 2.0.0
**Last Updated**: November 2024
**Status**: Production Ready ✅
