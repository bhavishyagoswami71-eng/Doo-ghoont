# DO GHOONT - Coffee Shop Management System

## 📱 Features

### 🛍️ Customer Website (index.html)
- Modern Gen-Z design with smooth animations
- Add to cart functionality
- UPI payment with QR code (9837382994@fam)
- Cash on Delivery option
- Order tracking
- Customer reviews

### 👨‍💼 Admin Dashboard (admin.html)
- Manage all orders
- Confirm/Reject UPI payments
- Update order status (Pending → Confirmed → Delivered)
- Manage products (add, edit, delete)
- Mark items out of stock
- Analytics dashboard

## 🚀 Deployment on Vercel

### Files Included:
1. **index.html** - Customer ordering website
2. **admin.html** - Owner/admin dashboard
3. **vercel.json** - Vercel configuration

### How to Deploy:

1. **Create a GitHub Repository:**
   - Go to https://github.com/new
   - Name: `do-ghoont`
   - Create repository

2. **Upload Files to GitHub:**
   - Upload `index.html` to main branch
   - Upload `admin.html` to main branch
   - Upload `vercel.json` to main branch

3. **Connect to Vercel:**
   - Go to https://vercel.com
   - Click "New Project"
   - Select GitHub repository: `do-ghoont`
   - Click "Deploy"

4. **Get Your Links:**
   - Main site: `https://do-ghoont.vercel.app/`
   - Admin: `https://do-ghoont.vercel.app/admin.html`

## 💳 Payment Details

**UPI ID:** 9837382994@fam  
**QR Code:** Generated automatically in checkout

## 🎯 How It Works

### Customer:
1. Browse menu items
2. Add to cart
3. Enter delivery details
4. Choose payment method:
   - **UPI:** Scan QR or use UPI ID → Confirm payment
   - **COD:** Order confirmed instantly
5. Order appears in "Your Orders"

### Owner:
1. Go to `/admin.html`
2. **Orders Tab:**
   - See all customer orders
   - For UPI orders: Click "Confirm Payment" after payment received
   - Click "Reject" if payment failed
   - Update order status
3. **Products Tab:**
   - Edit prices
   - Mark out of stock
   - Add new products
4. **Analytics Tab:**
   - View total orders
   - Track revenue
   - See pending orders
   - Payment status overview

## 📊 Data Storage

All data stored in browser's localStorage (local storage):
- Orders
- Products
- Customer reviews

Data persists across sessions in same browser.

## 🔧 Customization

### Change Menu Items:
- Admin Dashboard → Products Tab → Add New Product

### Change UPI Number:
- Edit in `index.html` (line ~710)
- Search: `9837382994@fam`

### Change Colors:
- Edit CSS variables in both files:
  ```css
  --primary: #1a1a2e (dark)
  --accent: #ff006e (pink)
  --secondary: #00d4ff (cyan)
  ```

### Change Business Name:
- Replace "DO GHOONT" with your name in headers

## 🆘 Support

If you face any issues:
1. Clear browser cache (Ctrl+Shift+Delete)
2. Check browser console for errors (F12)
3. Ensure JavaScript is enabled
4. Use Chrome/Firefox for best experience

## 📝 License

Created for DO GHOONT Coffee Shop - 2024

---

**Ready to launch?** Deploy to Vercel and share your unique links! 🚀
