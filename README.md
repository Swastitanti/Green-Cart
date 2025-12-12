# 🛒 GreenCart – Online Grocery Store

GreenCart is a **full-stack MERN (MongoDB, Express, React, Node.js)** grocery app. Customers can browse products, manage a shopping cart, save addresses, and place orders via **Cash on Delivery (COD)** or **Stripe Online Payments**. Sellers/Admins can manage products and view all orders.

👉 Live demo: [green-cart-o6el.vercel.app](https://green-cart-o6el.vercel.app)

---

##  Features

###  User
- Register & login using JWT & cookies
- Browse categories and products with offers
- Add/remove items in the cart
- Save delivery addresses
- Checkout with:
  - **Cash on Delivery (COD)**
  - **Stripe Online Payment** (secure with webhook order updates)
- View order history and real-time payment status

###  Seller/Admin
- Secure login (email + password via environment vars)
- Add / edit / delete products (with images hosted on Cloudinary)
- View all customer orders with payment status

---

##  Tech Stack

| Layer      | Technology                          |
|------------|--------------------------------------|
| Frontend   | React + Vite, Tailwind CSS           |
| Backend    | Node.js, Express, JWT auth           |
| Database   | MongoDB Atlas with Mongoose ODM      |
| Storage    | Cloudinary for product images        |
| Payments   | Stripe Checkout & Webhooks           |
| Hosting    | Vercel (frontend ), render (backend) |

---
## 📸 Screenshots

### 👤 User Side
- **Home Page**
  ![Home](./ScreenShots/GreenCart_Banner_section.png)

- **All Products Page**
  ![All Products](./ScreenShots/GreenCart_AllProducts_section.png/)

- **Single Product Page**
  ![Product Page](./ScreenShots/GreenCart_productFullview_section.png)

- **BestSeller Products**
  ![BestSeller](./ScreenShots/GreenCart_BestSeller_section.png)

- **Cart Page**
  ![Cart](./ScreenShots/GreenCart_Cart_section.png)

- **Address Page**
  ![Address](./ScreenShots/GreenCart_Address_section.png)

- **Online Payment Page**
  ![Online Payment](./ScreenShots/GreenCart_OnlinePayment_section.png)

- **My Orders Page**
  ![My Orders](./ScreenShots/GreenCart_MyOrder_section.png)


### 🛍️ Seller/Admin Side
- **Seller Login**
  ![Seller Login](./ScreenShots/GreenCart_Seller_login.png)

- **Seller Dashboard (Home)**
  ![Seller Home](./ScreenShots/GreenCart_SellerAddProduct_section.png)

- **Seller Product List**
  ![Seller Product List](./ScreenShots/GreenCart_SellerProductList_section.png)

- **Seller Orders**
  ![Seller Orders](./ScreenShots/GreenCart_SellerOrder_section.png)

---

## 📜 License

MIT License

Copyright (c) 2025 Swasti Kumari

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
