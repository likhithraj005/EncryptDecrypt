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
    
## Outputs
<img width="1440" alt="output1" src="https://github.com/user-attachments/assets/27ebcaf9-a0e4-4a53-babe-714c772ea83a">
<img width="1440" alt="output7" src="https://github.com/user-attachments/assets/2b8fa2d8-39da-43d6-a2f1-6d132766291a">
<img width="1440" alt="output6" src="https://github.com/user-attachments/assets/148134cc-c9f8-4900-9f42-4dc656412291">
<img width="1440" alt="output5" src="https://github.com/user-attachments/assets/53b08af0-f624-4368-8901-bc31b9d85ce0">
<img width="1440" alt="output4" src="https://github.com/user-attachments/assets/4cff7f20-7117-497d-82a7-44fc3e6c2398">
<img width="1440" alt="output3" src="https://github.com/user-attachments/assets/af304958-6ee4-4144-8613-481ee03e1c95">
<img width="1440" alt="output2" src="https://github.com/user-attachments/assets/b216f8b6-312a-4548-b388-615a22713256">
<img width="1440" alt="output8" src="https://github.com/user-attachments/assets/d7e41cbe-4e37-496c-92c4-ac3c2825eda9">
<img width="1440" alt="output9" src="https://github.com/user-attachments/assets/241688d1-e1a7-454f-9970-801cf655f444">


## Contributing

Contributions are welcome! Please fork the repository and submit a pull request with your changes. Ensure that your contributions follow the project's coding standards.
