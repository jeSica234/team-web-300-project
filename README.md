# team-web-300-project
# Online Fee Payment System

An online fee payment system built with PHP and MySQL.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Introduction

This project is an online fee payment system that allows users to pay fees online. It includes functionalities such as user registration, login, payment processing, and viewing payment history.

## Features

- User registration and login
- Fee payment for different categories
- Upload payment receipts
- View payment history

## Installation

Follow these steps to install the project:

1. Clone the repository
    bash
 git clone https://github.com/jeSica234/team-web-300-project.git
    cd online-fee-payment-system
    

2. Set up the database
    - Create a MySQL database named `fee_payment_system`.
    - Import the `database.sql` file located in the root directory of the project.

3. Configure the database connection
    - Edit the `config.php` file and update your database credentials:
    php
    <?php
    $servername = "localhost";
    $username = "root";
    $password = "";
    $dbname = "fee_payment_system";

    $conn = new mysqli($servername, $username, $password, $dbname);

    if ($conn->connect_error) {
        die("Connection failed: " . $conn->connect_error);
    }
    ?>
    ```

4. Run the application
    - Open the project in your web browser: http://localhost/online-fee-payment-system.

## Usage

1. Register as a new user.
2. Log in with your credentials.
3. Navigate to the payment page and make a payment.
4. Upload the payment receipt.
5. View payment history.

## Contributing

Contributions are welcome! Follow these steps:

1. Fork the repository.
2. Create a new branch: git checkout -b feature-name.
3. Make your changes and commit them: git commit -m 'Add some feature'.
4. Push to the branch: git push origin feature-name.
5. Submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.



## Contact

Your Name - [your-email@example.com](mailto:your-email@example.com)

Project Link: [https://github.com/your-username/online-fee-payment-system](https://github.com/your-username/online-fee-payment-system) 


<img width="932" alt="dues" src="https://github.com/jeSica234/team-web-300-project/assets/166191795/c1cb63fe-011e-4e7e-a12d-fae76d784438">

<img width="955" alt="history" src="https://github.com/jeSica234/team-web-300-project/assets/166191795/9810ed7e-63fb-416c-a735-c8de0357390f">
<img width="948" alt="history_ss" src="https://github.com/jeSica234/team-web-300-project/assets/166191795/ebaa3c1f-3441-4eb1-bf89-b5e1e316d77c">
<img width="949" alt="index" src="https://github.com/jeSica234/team-web-300-project/assets/166191795/b0a4e8cd-5692-4422-a4a1-72d26902ff15">

<img width="884" alt="payment" src="https://github.com/jeSica234/team-web-300-project/assets/166191795/9ffc4be1-404c-4ca8-89b1-aee47ad355b7">

<img width="953" alt="signin" src="https://github.com/jeSica234/team-web-300-project/assets/166191795/7547cb14-8934-4630-bf0f-b2a08f2690e3">

<img width="952" alt="signup" src="https://github.com/jeSica234/team-web-300-project/assets/166191795/0c91e760-0c1f-43e6-9b3d-0462939e749e">

<img width="949" alt="user" src="https://github.com/jeSica234/team-web-300-project/assets/166191795/16ff9e52-77e5-429f-8669-a71b9f6ff92e">

