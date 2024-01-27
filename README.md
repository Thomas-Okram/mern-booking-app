MERN Booking App Setup:

Follow these steps to set up the MERN Booking App https://mern-hotel-booking-app-14hp.onrender.comly.

Prerequisites:

Ensure Node.js is installed.

Backend:

1. Clone the repository:

git clone https://github.com/Thomas-Okram/mern-booking-app.git

cd mern-booking-app

2. Create .env in the backend folder with MongoDB, Cloudinary, Stripe, and JWT secret keys.

3. Set up MongoDB Atlas, obtain a connection string, and add it to .env.

4. Set up Cloudinary and Stripe accounts, retrieve keys, and add them to .env.

5. Start the backend:
   cd backend
   npm install
   npm start

Frontend:

1. In the frontend folder, create .env with the backend URL.
   VITE_API_BASE_URL=
   VITE_STRIPE_PUB_KEY=

2. Install frontend dependencies and start the app:
   cd frontend
   npm install
   npm run dev

Automated Tests:

1. In the e2e-tests folder, create .env.e2e with the test MongoDB connection string.

2. Install dependencies and run tests:
   cd e2e-tests
   npm install
   npm run test
