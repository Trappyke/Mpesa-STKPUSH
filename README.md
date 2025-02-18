STK Push Payment System
Description

The STK Push Payment System is a PHP-based application designed to facilitate M-Pesa STK Push payments. This system allows users to initiate payments through a web interface, leveraging the M-Pesa API to process transactions. The application is structured to handle payment requests, generate access tokens for API authentication, and manage callbacks for transaction status updates.
Features

    Access Token Generation: Securely generates access tokens for API authentication using the M-Pesa API.
    Payment Initiation: Allows users to initiate payments by entering their phone number, account number, and the amount to be paid.
    Transaction Processing: Processes payment requests through the M-Pesa API, handling the STK Push process.
    Callback Management: Manages callbacks for transaction status updates, ensuring users are informed of the transaction outcome.

Tech Stack

    PHP: The primary programming language used for server-side logic.
    M-Pesa API: Utilizes the M-Pesa API for payment processing.
    cURL: For making HTTP requests to the M-Pesa API.

Getting Started
Prerequisites

    A web server with PHP installed.
    Access to the M-Pesa API, including a valid Consumer Key and Consumer Secret.

Installation

    Clone the repository or download the files to your web server.
    Update the accessToken.php file with your M-Pesa Consumer Key and Consumer Secret.
    Ensure the index.php file is correctly configured to handle payment requests and callbacks.
    Test the application by accessing the index.php file through a web browser.

Usage

    Navigate to the index.php file in your web browser.
    Enter your phone number, account number, and the amount you wish to pay.
    Click "Pay Now" to initiate the payment process.
    Follow the on-screen instructions to complete the payment.

Contributing

Contributions are welcome. Please feel free to submit pull requests or open issues for any improvements or bug fixes.
License

This project is licensed under the MIT License. See the LICENSE file for details.
Contact

For any questions or support, please open an issue on this repository.