# AUTOX SPARES

### GenAI-Powered Automobile Spare Parts Shop

> **Quality Parts. Better Performance. Better Prices.**

AUTOX SPARES is a modern, responsive automobile spare-parts shopping website designed to help customers easily discover, compare, and purchase spare parts for cars and bikes.

The application provides product images, original prices, discounts, discounted prices, vehicle compatibility, product specifications, search, filtering, shopping cart, checkout, offers, and AI-assisted product discovery.

---

## 📌 Project Overview

Finding the correct automobile spare part can be difficult because customers need to compare different brands, prices, vehicle compatibility, availability, and discounts.

AUTOX SPARES provides a single platform where customers can:

* Browse automobile spare parts
* Search for required products
* Filter products by category, vehicle, brand, price, and discount
* View product images and specifications
* Compare original and discounted prices
* Find products based on vehicle type
* Add products to cart
* Manage quantities
* View discounts and total prices
* Proceed through checkout
* Get AI-assisted product discovery and assistance

---

## 🎯 Objectives

The main objectives of AUTOX SPARES are:

* To develop a functional automobile spare-parts shopping website.
* To provide a user-friendly product catalogue.
* To display product images, prices, discounts, ratings, and stock.
* To provide search, filtering, and sorting functionality.
* To help users find products based on vehicle compatibility.
* To provide AI-assisted natural-language product discovery.
* To implement shopping-cart and checkout functionality.
* To provide an administration interface for product and order management.
* To create a responsive interface for desktop, tablet, and mobile devices.

---

## ✨ Features

### 🏠 Home Page

* Modern automobile-themed design
* AUTOX SPARES branding
* Hero section
* Featured categories
* Special offers
* Navigation menu
* Search
* Shopping cart

### 🔧 Spare Parts Catalogue

Products are organized into categories such as:

* Engine Parts
* Brake Parts
* Suspension Parts
* Electrical Parts
* Filters
* Batteries
* Tyres & Wheels
* Lighting
* Car Accessories
* Bike Accessories

Each product contains:

* Product image
* Product name
* Brand
* Vehicle compatibility
* Original price
* Discount percentage
* Discounted price
* Rating
* Stock status
* Product specifications

---

## 🔍 Search and Filtering

Users can search for products using:

* Product name
* Spare-part type
* Brand
* Vehicle
* Category

### Filters

* Category
* Vehicle type
* Brand
* Price range
* Discount percentage

### Sorting

* Price: Low to High
* Price: High to Low
* Highest Discount
* Top Rated
* New Arrivals

---

## 🤖 GenAI Integration

The project includes an AI-assisted product discovery concept.

Users can enter natural-language requests such as:

> "I need brake pads for a Honda car under ₹3000."

The AI assistance layer can interpret the user's requirement and help identify relevant products from the structured catalogue.

The GenAI component can be used for:

* Natural-language product search
* Product discovery
* Customer assistance
* Product recommendations
* Product-description generation
* Understanding customer requirements

### Important

Product facts such as:

* Price
* Discount
* Stock
* Vehicle compatibility

should come from the application's structured product data rather than being invented by the AI.

---

## 🚗 Shop by Vehicle

Users can browse products based on vehicle manufacturers.

### Cars

* Maruti Suzuki
* Hyundai
* Tata
* Honda
* Toyota
* Mahindra
* Kia

### Bikes

* Hero
* Honda
* TVS
* Yamaha
* Bajaj
* Royal Enfield
* KTM

---

## 💰 Discounts and Offers

The website displays:

* Original price
* Discount percentage
* Discounted price
* Offer badges
* Special promotions

Example:

| Product                  | Original Price | Discount | Sale Price |
| ------------------------ | -------------: | -------: | ---------: |
| Bosch Brake Pad Set      |         ₹2,499 |      20% |     ₹1,999 |
| Castrol Engine Oil 5W-40 |         ₹1,299 |      15% |     ₹1,104 |
| Exide Car Battery        |         ₹8,999 |      10% |     ₹8,099 |
| Philips LED Headlight    |         ₹3,499 |      25% |     ₹2,624 |
| SKF Wheel Bearing        |         ₹1,799 |      18% |     ₹1,475 |

---

## 🛒 Shopping Cart

The cart allows customers to:

* Add products
* Remove products
* Increase quantity
* Decrease quantity
* View subtotal
* View total discount
* View delivery charges
* View grand total

Example:

```text
Subtotal       : ₹8,500
Discount       : -₹1,200
Delivery       : ₹100
-----------------------
Grand Total    : ₹7,400
```

---

## 📦 Checkout

The checkout page collects:

* Full Name
* Mobile Number
* Email
* Address
* City
* State
* PIN Code

The system displays the order summary before placing the order.

After successful order placement, an order ID is generated and an order confirmation is displayed.

> The current project uses simulated checkout/payment functionality.

---

## 👨‍💼 Admin Dashboard

The admin dashboard can provide:

### Dashboard Statistics

* Total Products
* Total Orders
* Total Customers
* Total Revenue

### Product Management

* Add Product
* Edit Product
* Delete Product
* Update Price
* Update Discount
* Update Stock
* Upload Product Image

### Order Management

* Pending
* Confirmed
* Shipped
* Delivered
* Cancelled

---

## 🛠️ Technology Stack

### Frontend

* React
* Vite
* JavaScript / TypeScript
* Tailwind CSS
* Lucide React

### Backend

If backend functionality is enabled:

* Node.js
* Express.js
* REST API

### Database

If persistent storage is enabled:

* MongoDB

### AI

* Generative AI API / model selected during implementation

### Development Tools

* Visual Studio Code
* Codex
* Git
* GitHub

---

## 📁 Project Structure

A recommended project structure is:

```text
AUTOX-SPARES/
│
├── frontend/
│   ├── public/
│   │   └── images/
│   │
│   ├── src/
│   │   ├── components/
│   │   │   ├── Navbar
│   │   │   ├── Footer
│   │   │   ├── ProductCard
│   │   │   ├── CategoryCard
│   │   │   ├── SearchBar
│   │   │   └── FilterPanel
│   │   │
│   │   ├── pages/
│   │   │   ├── Home
│   │   │   ├── Products
│   │   │   ├── ProductDetails
│   │   │   ├── Offers
│   │   │   ├── Cart
│   │   │   ├── Checkout
│   │   │   ├── About
│   │   │   └── Contact
│   │   │
│   │   ├── data/
│   │   │   └── products
│   │   │
│   │   ├── App
│   │   └── main
│   │
│   └── package.json
│
├── backend/
│   ├── routes/
│   ├── controllers/
│   ├── models/
│   ├── services/
│   └── server
│
├── README.md
└── .env.example
```

---

## 🚀 Installation

### 1. Clone the Repository

```bash
git clone <your-github-repository-url>
```

Move into the project folder:

```bash
cd AUTOX-SPARES
```

---

## 💻 Frontend Setup

Move into the frontend directory:

```bash
cd frontend
```

Install dependencies:

```bash
npm install
```

Start the development server:

```bash
npm run dev
```

The terminal will display the local development URL.

Open that URL in your browser.

---

## ⚙️ Backend Setup

If the project includes a backend:

```bash
cd backend
```

Install dependencies:

```bash
npm install
```

Start the backend:

```bash
npm run dev
```

---

## 🔐 Environment Variables

Create a `.env` file if required.

Example:

```env
VITE_API_URL=http://localhost:8000

AI_API_KEY=your_api_key_here

DATABASE_URL=your_database_connection_string
```

Do not upload API keys or passwords to GitHub.

---

## 🧪 Testing

Before deployment, test the following:

* [ ] Homepage loads correctly
* [ ] Navigation works
* [ ] Product images load
* [ ] Search works
* [ ] Filters work
* [ ] Sorting works
* [ ] Product details open correctly
* [ ] Discounts are calculated correctly
* [ ] Products can be added to cart
* [ ] Quantity can be changed
* [ ] Products can be removed
* [ ] Checkout works
* [ ] Order confirmation works
* [ ] AI assistance works if configured
* [ ] Admin dashboard works
* [ ] Website is responsive
* [ ] No console errors
* [ ] No broken images

---

## 📱 Responsive Design

AUTOX SPARES is designed to work across:

* Desktop
* Laptop
* Tablet
* Mobile

The layout automatically adapts to different screen sizes.

---

## 🔒 Security Considerations

For a production deployment:

* Store API keys securely.
* Never expose private API keys in frontend code.
* Validate user input.
* Implement secure authentication.
* Protect admin routes.
* Validate product and order information on the server.
* Use HTTPS.
* Implement proper database access controls.

---

## 🔮 Future Scope

Future versions can include:

* Online payment gateway
* Real-time inventory
* Supplier integration
* Delivery tracking
* Customer accounts
* Order history
* Saved vehicles
* Voice-based product search
* Multilingual support
* AI-powered spare-part identification from images
* Personalized recommendations
* Mobile Android/iOS application
* Sales and inventory analytics
* Cloud deployment

---

## 👨‍🎓 Project Information

**Project Name:** AUTOX SPARES – GenAI-Powered Automobile Spare Parts Shop

**Student:** Boya Shiva Kumar

**Department:** Computer Science and Engineering – Data Science

**Guide:** M Prithvi Sir

**Academic Year:** 2026–2027

**Project Type:** Learning Block 1 – Mini Project

---

## 📄 License

This project is developed for academic and educational purposes.

© 2026 AUTOX SPARES
