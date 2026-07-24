# Virtual Wallet System

A virtual wallet system built with Laravel 6 and Flutterwave's Rave Payment Gateway.

## Features

1. User registration and authentication
2. Deposit funds into an online wallet
3. Transfer funds to other users via the online wallet
4. Withdraw funds to bank accounts supported by Rave
5. Email notification after registration

## Tech Stack

- **Framework:** Laravel 6
- **Payment Gateway:** Flutterwave Rave
- **Front-end:** Bootstrap, jQuery, Popper.js
- **Development Tools:** Laravel Mix, Axios, Lodash, Vue.js

## Prerequisites

- PHP 7.2 or higher
- MySQL database
- Composer
- Node.js and npm

## Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/Ojsholly/virtual-wallet
   ```

2. **Install Composer dependencies:**

   ```bash
   composer install
   ```

3. **Install NPM dependencies:**

   ```bash
   npm install
   ```

   or

   ```bash
   yarn
   ```

4. **Create a copy of the `.env` file:**

   ```bash
   cp .env.example .env
   ```

   Update the `.env` file with your database connection details and other environment variables.

5. **Generate an application key:**

   ```bash
   php artisan key:generate
   ```

6. **Run database migrations:**

   ```bash
   php artisan migrate
   ```

7. **Add Rave payment gateway environment variables:**

   ```
   RAVE_TEST_PUBLIC_KEY=
   RAVE_TEST_SECRET_KEY=
   RAVE_SECRET_KEY=
   RAVE_PUBLIC_KEY=
   ```

   Ensure to use the test keys for development. For production, replace the test keys with the live keys from your Flutterwave dashboard.

8. **Start the development server:**

   ```bash
   php artisan serve
   ```

   The application will be available at `http://localhost:8000`.

## Usage

1. **Register a new user**
2. **Deposit funds into the wallet**
3. **Transfer funds to other users**
4. **Withdraw funds to a bank account**

## Contributing

Contributions are welcome! Please feel free to submit a pull request or open an issue for any bugs or feature requests.

## License

This project is licensed under the [MIT License](https://choosealicense.com/licenses/mit/).