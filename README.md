# React Express Razorpay Integration

This project demonstrates the integration of Razorpay API with a React frontend and an Express backend. Razorpay is a payment gateway solution that allows businesses to accept online payments.

## Features

- Integration of Razorpay API for payment processing.
- React frontend for user interface.
- Express backend for handling API requests and communicating with the Razorpay API.
- Utilization of Postman for testing API endpoints.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/praball/RazorpayAPI-React

2. Install dependencies for both client and server:

   ```bash
   cd RazorpayAPI-React/client
   npm install

   cd ../server
   npm install

## Usage

1. Start the Express Server:
   ```bash
   cd RazorpayAPI-React/server
   npm start

2. Start your React Frontend:
   ```bash
   cd RazorpayAPI-React/client
   npm start
3. Access the application in your browser at http://localhost:3000.
4. Use Postman to test the API endpoints located at http://localhost:YOUR_PORT/api.

## Configuration:

1. Obtain API keys from Razorpay by signing up on their website. (You may have to provide your PAN number as well, KYC not required for testing mode)

2. Configure your Razorpay API keys in the Express backend for making requests, thereby set up the .env file.

3. Make sure to configure CORS settings if needed to allow requests from the React frontend.

## Contributing

Contributions are welcome! Please feel free to submit pull requests or open issues for any features, bugs, or suggestions.

## License

This project is licensed under the MIT License - see the LICENSE file for details.
