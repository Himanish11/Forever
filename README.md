Forever - E-Commerce Clothing Store

"Forever" is a full-featured e-commerce website built using the MERN (MongoDB, Express, React, Node.js) stack. This project is a clothing store that offers a seamless shopping experience, complete with user authentication, order management, and a fully functional admin dashboard to manage products. Customers can easily browse, filter, and purchase items through a secure and integrated payment gateway.

Features

User Features
- Sign Up & Login: Users can create accounts or log in securely to make purchases.
- Product Catalog: Browse through a wide selection of clothing items with detailed product pages.
- Product Filtering: Filter products based on categories, size, color, and price.
- Shopping Cart: Add items to the cart and proceed to checkout.
- Order Management: View order history, track orders, and manage purchases.
- Secure Payment Gateway: Pay securely through an integrated payment system.

Admin Features
- Admin Dashboard: Manage the entire catalog of products, including adding, editing, and removing items.
- Product Management: Upload new products with images, descriptions, and pricing.
- Order Management: View customer orders and update their statuses (e.g., processing, shipped, delivered).
- User Management: Manage user accounts and view customer details.

Technologies Used
- Frontend: React.js
- Backend: Node.js, Express.js
- Database: MongoDB (Mongoose for ORM)
- Authentication: JWT (JSON Web Tokens) and bcrypt for secure password hashing.
- Payment Gateway: Stripe API for secure online payments.
- Deployment: Hosted on Render (both frontend and backend).

Installation and Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/forever-clothing-store.git
   ```

2. Navigate into the project directory:
   ```bash
   cd forever-clothing-store
   ```

3. Install dependencies for both frontend and backend:
   ```bash
   npm install
   cd client
   npm install
   ```

4. Set up environment variables:
   - Create a `.env` file in the root directory.
   - Add the following keys:
     ```
     MONGO_URI=<your-mongo-db-connection-string>
     JWT_SECRET=<your-jwt-secret>
     STRIPE_SECRET_KEY=<your-stripe-secret-key>
     ```

5. Start the application:
   - Backend:
     ```bash
     npm run server
     ```
   - Frontend:
     ```bash
     cd client
     npm start
     ```

6. The application will be available on `http://localhost:3000` for the frontend and `http://localhost:5000` for the backend.
