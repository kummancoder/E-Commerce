# E-Commerce Website

This project is a full-stack **E-Commerce Website** built using the **MERN stack** (MongoDB, Express.js, React.js, and Node.js). The website offers a seamless shopping experience with features for browsing products, managing a cart, and processing orders.

---

## Features

### User Features

- **Browse Products**: View a variety of products with detailed descriptions and images.
- **Search and Filter**: Search for products and filter them by categories, price range, etc.
- **Shopping Cart**: Add, update, or remove items from the cart.
- **Order Management**: Place orders and view order history.
- **Secure Payments**: Make payments securely using the integrated **Stripe** payment gateway.

### Admin Features

- **Manage Products**: Add, edit, or delete products.
- **Manage Orders**: View and update the status of customer orders.
- **User Management**: View and manage registered users.

---

## Tech Stack

- **Frontend**: React.js with Redux for state management.
- **Backend**: Node.js with Express.js.
- **Database**: MongoDB for data storage.
- **Authentication**: JSON Web Tokens (JWT) for secure user authentication.
- **Payment Gateway**: Stripe for handling secure payments.
- **Styling**: Tailwind CSS.

---

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/kummancoder/E-Commerce.git
   ```

2. Navigate to the project directory:

   ```bash
   cd E-Commerce
   ```

3. Install dependencies for both frontend and backend:

   ```bash
   cd frontend
   npm install
   cd ../backend
   npm install
   ```

4. Set up environment variables in a `.env` file:

   ```env
   MONGO_URI=<your-mongodb-connection-string>
   JWT_SECRET=<your-jwt-secret>
   STRIPE_SECRET_KEY=<your-stripe-secret-key>
   STRIPE_PUBLISHABLE_KEY=<your-stripe-publishable-key>
   ```

5. Start the development servers:

   - For the backend:
     ```bash
     cd backend
     npm run dev
     ```
   - For the frontend:
     ```bash
     cd frontend
     npm start
     ```

6. Open the application in your browser at `http://localhost:3000`.

---

## Usage

1. **User Mode**:

   - Browse products, add them to the cart, and proceed to checkout.
   - Make secure payments using Stripe.
   - Log in to view your order history and manage your account.

2. **Admin Mode**:

   - Access the admin panel to manage products, orders, and users.

---

## Future Improvements

- Add real-time inventory tracking.
- Implement product reviews and ratings.
- Optimize performance for larger datasets.
- Add multi-language support.

---

## Contributing

Contributions are welcome! If you'd like to contribute, please fork the repository and submit a pull request with your changes.

---

## Contact

For any questions or feedback, please contact:

- **Name**: Kumman Das Dhakad
- **Email**: Kummandhakad@gmail.com 
- **GitHub**: https://github.com/kummancoder

