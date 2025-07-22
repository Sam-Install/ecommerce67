# ecommerce67


# MyStack Ecommerce App 🛒

A full-featured **MERN** (MongoDB, Express, React, Node.js) ecommerce web app, built by following GreatStack tutorial. It includes user authentication, shopping cart, checkout (COD & Stripe), order history, and address management.





## 🧩 Core Features

- **Product Catalog**: Browse items by category, view images, prices (original & discounted).
- **User Auth**: Login & signup with JWT-based sessions.
- **Shopping Cart**: Add/remove/update quantities; persists across sessions.
- **Address Book**: Store multiple shipping addresses.
- **Checkout**:
  - **Cash on Delivery (COD)**: Instant order placement.
  - **Stripe Checkout**: Secure online payments.
- **Order Management**: View past orders with details and status.
- **Backend APIs**: RESTful design, protected routes via middleware.
- **State & Data Sync**: Cart sync with backend; global state managed via React Context.
- **Notifications**: Real-time feedback using toast messages.

---

## 🛠 Technologies & Tools

#### Frontend
- React, React Router v6
- React Context for global state
- Axios, react-hot-toast, TailwindCSS
#### Backend
- Node.js & Express
- MongoDB with Mongoose
- JSON Web Tokens for authentication
- Stripe API for payment integration
- Middleware: CORS, cookie-parser, custom auth
#### Environment & Deployment
- .env setup for JWT secret, Mongo URI, Stripe keys
- Optional hosting: Vercel (frontend), Heroku/Render (backend), MongoDB Atlas

---

## 🔧 Project Structure

