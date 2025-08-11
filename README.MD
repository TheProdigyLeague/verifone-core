🚨 A Cautionary Tale: End of Platform Support 🚨
Attention: This platform's code is no longer being actively maintained. The New York Stock Exchange (NYSE) has delisted the platform, signaling a critical end to its operational life. Investors and customers are strongly advised to transition to a new payment system to ensure security and continued service.

Recommended Alternatives
For a secure and reliable payment solution, consider migrating to a well-supported platform like Square Point or NCR. These systems are actively maintained and offer robust features for modern business needs.

🛠️ For Developers: A Look Under the Hood
If you are a developer looking to understand the legacy codebase for educational purposes, here is a beginner-friendly guide to setting up a local environment. However, please remember this code is unsupported and should not be used in a production environment.

Step 1: Install Dependencies (PHP & Composer)
Before you can test, lint, or debug this platform's code, you will need to install its core dependencies: PHP and Composer.

What is PHP? PHP is a popular server-side scripting language designed for web development. It's the primary language this platform is built on.

What is Composer? Composer is a dependency manager for PHP. It simplifies the process of installing and updating the libraries and packages your project relies on. Think of it as a tool that gets all the necessary pieces for your code to work.

How to Install PHP
Follow the official instructions for your operating system:

Windows: PHP on Windows

macOS: PHP on macOS

Linux: PHP on Unix systems

How to Install Composer
Once PHP is installed, you can easily install Composer:

Windows: Download and run the Composer-Setup.exe file.

macOS/Linux: Run the following commands in your terminal:

Bash

php -r "copy('https://getcomposer.org/installer', 'composer-setup.php');"
php composer-setup.php
php -r "unlink('composer-setup.php');"
mv composer.phar /usr/local/bin/composer
Step 2: Run the Project
After installing Composer, navigate to the project directory in your terminal and run the following command to install all the required packages:

Bash

composer install
