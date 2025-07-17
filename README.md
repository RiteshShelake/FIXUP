# FixUp - Fixers and Installers Xtreme Utility Platform

**FixUp** is a service appointment booking platform built with the MERN stack (MongoDB, Express.js, React.js, Node.js). It allows users to book various household services like electrician, carpenter, driver, and more.

## Features

- **User Authentication**: Secure login and registration with JWT.
- **Service Booking**: Browse and book household services.
- **Payment Integration**: Secure payments via Stripe.
- **Admin Dashboard**: Manage services, users, and bookings.

## Technologies Used

- **Frontend**: React.js
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Authentication**: JWT
- **Payment Gateway**: Stripe

## Getting Started

### Prerequisites

- Node.js
- MongoDB
- npm (Node Package Manager) or Yarn

### Installation

1. **Clone the repository:**
    ```bash
    git clone https://github.com/yourusername/fixup.git
    cd fixup
    ```

2. **Install dependencies:**
    ```bash
    cd server
    npm install
    cd ../client
    npm install
    ```

3. **Set up environment variables:**
    Create a `.env` file in the `server` directory with the following:
    ```env
    MONGO_URI=your_mongodb_uri
    JWT_SECRET=your_jwt_secret
    STRIPE_SECRET_KEY=your_stripe_secret_key
    ```

4. **Run the application:**
    ```bash
    # Start backend server
    cd server
    npm start

    # Start frontend server
    cd ../client
    npm start
    ```

5. **Visit the application:**
    Open your browser and go to `http://localhost:3000`

## License

   This project is licensed under the MIT License.
   [LICENSE](https://github.com/RIO-Repository/Fix-Up/blob/main/LICENSE) file for details.
   
## Our Contributors ✌️

<a href="https://github.com/RIO-Repository/Fix-Up/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=RIO-Repository/Fix-Up" />
</a>

Made with [contrib.rocks](https://contrib.rocks).
