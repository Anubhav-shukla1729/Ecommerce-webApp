# MERN E-Commerce

MERN E-Commerce is an innovative online shopping platform built on the MERN stack (MongoDB, Express.js, React, and Node.js). It provides businesses with a streamlined solution to set up and manage online stores with ease, while delivering a seamless shopping experience to customers.

## Features

- **Basic E-Commerce Functionalities**:  
  Product listings, sorting, detailed product views, shopping cart, and checkout.

- **Secure Card Payments**:  
  Integrated with Stripe to enable secure and efficient transactions.

- **Admin Panel**:  
  Manage orders and products easily through an intuitive admin panel.

- **Data Management**:  
  Mongoose facilitates sorting, filtering, and pagination queries.

- **Authentication**:  
  Secure user authentication with Passport.js strategies.

- **Email Communication**:  
  Nodemailer, configured with Gmail SMTP, handles order notifications and password reset emails.

- **User Profile**:  
  Allows users to create profiles and view their order history.


  ## Technical Details

**Frontend Stack**  
- React 18 with Tailwind CSS for responsive and modern styling.

**State Management**  
- Redux Toolkit with Async Thunk for efficient state handling.

**Routing**  
- React Router v6 for smooth navigation.

**Frontend Testing**  
- JSON-server is used for front-end testing.

**Backend Stack**  
- MongoDB for the database.
- REST API using Express.
- Authentication with Passport.js and Passport JWT strategies.
- MongoDB Atlas for cloud database hosting.

**Deployment**  
- Vercel for seamless server deployment with straightforward setup.

**Email Configuration**  
- Configurable environment variables for SMTP and email settings.

**Payments**  
- Integrated secure payments with Stripe’s PaymentIntent-based custom flow.



## MongoDB Collections

The application uses the following MongoDB collections:
- Brands
- Carts
- Categories
- Orders
- Products
- Users


## Getting Started

### Prerequisites

- Node.js and npm: Ensure both are installed on your machine.


### Installation

1. **Clone the Repository**  
   Clone this repository to your local environment:
   ```bash
   git clone https://github.com/your-username/MERN-E-Commerce.git
   npm install

Create a .env file in the root directory with the following environment variables:
   ```plaintext
STRIPE_SECRET_KEY=your_stripe_secret_key
MONGODB_URI=your_mongodb_uri
EMAIL_HOST=your_email_host
EMAIL_PORT=your_email_port
EMAIL_USER=your_email_user
EMAIL_PASSWORD=your_email_password

```bash
npm start





---

This version uses code blocks to contain each section and better represents Markdown formatting for `README.md`. Let me know if you’d like further adjustments!

