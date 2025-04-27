# 🛒 Grocery Store App

## 📋 Overview
A modern React-based grocery store application where users can browse products, add them to a cart, and manage inventory via an admin dashboard. Includes search functionality, product filtering, and responsive design.

---

## ✨ Features

### 🛍️ User Features
- Browse products by category (Fruits, Vegetables, Dairy, Bakery, Meat)
- Search for specific products
- Add products to shopping cart
- View and modify cart contents
- Responsive design (mobile-friendly)

### 🛠️ Admin Features
- Secure login system
- Add new products
- Delete existing products
- View all products in dashboard

---

## ⚙️ Technologies Used
- [React 18+](https://react.dev/)
- [React Router 6+](https://reactrouter.com/)
- React Hooks (`useState`, `useEffect`)
- CSS for styling
- JSON for data

---

## 🚀 Installation

1. **Clone the repository:**
    git clone [repository-url]
    

2. **Navigate to project directory:**
    
    cd grocery-store-app
  

3. **Install dependencies:**
    
    npm install
    

4. **Start development server:**
    npm run dev
    

---

## 🗂️ Project Structure

src/
├── components/
│   ├── Navbar.jsx
│   ├── Home.jsx
│   ├── ProductList.jsx
│   ├── ProductForm.jsx
│   ├── ShoppingCart.jsx
│   ├── AdminLogin.jsx
│   └── AdminDashboard.jsx
├── data/
│   └── db.json
├── App.jsx
├── main.jsx
└── index.css


---

## 🎯 Usage

### User Flow
1. Browse products on the Home or Product List pages
2. Click on any product to view its details
3. Add products to the cart
4. Review cart selections
5. (Optional) Proceed to checkout (UI only)

### Admin Flow
1. Click "Admin" in navigation
2. Login using:
   - **Username**: `admin`
   - **Password**: `admin123`
3. Access dashboard to:
   - Add new products
   - Delete existing products

---

## ⚙️ Configuration

- **Database**:  
  Modify data in:
  src/data/db.json


---

## 🛑 Known Limitations
- Data resets on page refresh (no persistent backend)
- No actual payment processing integration
- Admin credentials are hardcoded (frontend-only, not production-secure)

---

## 🛠️ Future Improvements
- Add real user authentication
- Implement backend API for persistent data
- Enable product editing
- Implement full checkout process
- Add product reviews and ratings

---

## 📄 License
This project is open-source and available under the [MIT License](LICENSE).

---

## Authors
1. Brian Cheruiyot
2. Titus Kiprono
3. Ryan Ngugi


