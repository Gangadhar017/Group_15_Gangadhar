# 🏬 Wholesale / Bulk Order Management System – Admin Panel  
Frontend for Wholesaler/Seller (Admin) operations.  
Built for handling B2B workflows such as account approvals, tiered pricing, bulk ordering, inventory control, order processing, and credit limits.

---

## 🚀 Project Overview
Unlike normal B2C e-commerce, wholesale involves:
- Retailers buying in bulk
- Tier-based pricing
- Minimum order quantities (MOQ)
- Credit limits
- Reorder workflows
- Bulk CSV uploads
- Account approval before buyers can see prices

This Admin Panel is designed for the **Wholesaler (Seller)** to manage all internal B2B operations.

---

## 🎯 Features (Admin Panel)

### 👤 **Account Approval Dashboard**
- Approve/reject retailer registrations  
- Bulk approval  
- Status badges (pending / approved / rejected)  

### 💰 **Pricing Engine (Tiered Pricing)**
- Create dynamic pricing tiers  
- Example:  
  - Price A: 1–50 units  
  - Price B: 51+ units  
- Live price preview by quantity  

### 📦 **Inventory Management**
- View and edit product stock  
- Bulk upload inventory using CSV  
- Auto-detect low stock items  

### 📑 **Order Management**
- View incoming orders  
- Update order status: New → Processing → Shipped  
- Add tracking numbers  
- Generate invoice (PDF – mock integration)  

### 💳 **Credit Management**
- Set retailer credit limits  
- Block/unblock buyers  
- View credit usage  

---

## 🛠️ Tech Stack

### Frontend
- **React (Vite)**  
- **Redux Toolkit**  
- **TailwindCSS**  
- **Axios**  
- **React Router**  

### Backend (Mock Server)
- **Node + Express**  
- **CORS**  
- **Multer (CSV upload)**  
- **In-memory JSON DB**

---

## 📁 Folder Structure
