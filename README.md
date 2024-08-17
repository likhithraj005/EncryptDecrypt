# EncryptDecrypt

EncryptDecrypt is a Java application that allows users to securely hide and unhide files using encryption techniques. The application provides a way to manage hidden files with added security through email-based OTP (One-Time Password) verification.

## Features

- **File Hiding**: Encrypts and hides files specified by the user.
- **File Revealing**: Decrypts and reveals previously hidden files upon OTP verification.
- **Database Integration**: Maintains a record of hidden and revealed files.

## Getting Started

### Prerequisites

- Java and Maven for dependencies
- MySQL database

### Installation

1. **Clone the Repository:**
    ```bash
    git clone https://github.com/likhithraj005/EncryptDecrypt.git
    ```

2. **Navigate to the Project Directory:**
    ```bash
    cd EncryptDecrypt
    ```

3. **Compile the Java Files:**
    ```bash
    javac src/*.java
    ```

4. **Run the Application:**
    ```bash
    java src.Main
    ```

### Configuration

1. **Set Up the Database:**
    - Ensure MySQL is installed and running.
    - Create a database and configure the `database.properties` file with your database connection details.

2. **SMTP Configuration:**
    - Update the email configuration in `email.properties` with your SMTP server details for sending OTP emails.

## Usage

1. **Login/Signup:**
    - Press `1` to log in or `2` to sign up.
    - Enter your email address.
    - An OTP will be sent to your email. Enter the OTP to verify and log in.

2. **File Management:**
    - **Show Hidden Files**: Press `1` to list hidden files.
    - **Hide a New File**: Press `2` and provide the file path to encrypt and hide a new file.
    - **Show Exposed Files**: Press `3` to list all files that are currently exposed.
    - **Unhide a File**: Enter the ID of the file you wish to unhide.

## Example

Here's an example of how to use the application:

1. **Log In:**
    ```plaintext
    Welcome to the Application
    Press 1 to login
    Press 2 to signup
    Press 0 to exit
    ```

2. **Hide a File:**
    ```plaintext
    Enter the file path
    /path/to/your/file.txt
    ```

3. **Unhide a File:**
    ```plaintext
    Enter the id of file to unhide
    ```

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request with your changes. Ensure that your contributions follow the project's coding standards.
