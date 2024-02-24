# Artilugio

> E-commerce site built with MERN stack

### Environment Variables

Add your config variables in the config.env file in backend/config folder.

### Install Dependencies (Frontend)

```
cd frontend
npm i
```

### Install Dependencies (Backend)

```
npm i
```

### Seed Database

Use the following commeand to put some dummy products in that database.
Run it in the root folder.

```
npm run seeder
```
🚀 Features
Login/Signup User Account
Update Profile/Password User Account
Reset Password Mail using Sendgrid
Cart Add/Remove Items | Update Quantities
Save For Later Add/Remove Items
Wishlist Add/Remove Items
Products Pagination (Default 12 Products Per Page)
Product Search
Product Filters Based on Category/Ratings | Price Range
Shipping Info in Session Storage
My Orders (With All Filters)
Order Details of All Ordered Item
Users will receive mail when order placed with all details
Review Products User Account
Admin: Dashboard access to only admin roles
Admin: Update Order Status | Delete Order
Admin: Add/Update Products
Admin: Update User Data | Delete User
Admin: List Review of Product | Delete Review
Stock Management: Decrease stock of product when shipped
