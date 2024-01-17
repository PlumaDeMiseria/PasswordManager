# Password Manager 

**A simple password generator and manager with encryption capabilities.**

**Note: This manager is made for practicing, not recommended to use for store sensitive data**

## Features

- Generates strong, random passwords
- Saves passwords in an encrypted vault
- Encrypts the vault with Fernet and GPG for added security
- Allows viewing, searching, and copying saved passwords
- Built-in password strength meter
- Add your passwords into vault
  
## In Development
- **Multiple vaults for different categories**

## Problems
- CSPRNG
- Virtualenv
- Clear clipboard
- Using admin access to reveal key instead of start the manager

## Usage
**To install and run the program:**

1. **Install the repository:**
   - Download or clone the repository to your desired location.

2. **Start the main.py file:**
   - Open a terminal or command prompt in the repository's directory.
   - Execute the following command:

     ```bash
     python3 main.py
     ```

3. **Install missing libraries (if prompted):**
   - The program will automatically check for required libraries.
   - If any are missing, it will prompt you to install them using `pip3`.
   - Follow the on-screen instructions to complete the installation.

**Important notes:**

- **Python version compatibility:** The program requires Python version 3.10 or higher.
- **Administrative privileges:** Running the program may require administrative privileges for certain operations.


## Additional Notes

- The script automatically checks for and installs required libraries.
- Encryption keys are essential for accessing the vault. Store them securely (or use auto encryption system).
- Admin access is required for security and file operations.

## Contributing

Feel free to fork the repository and submit pull requests for improvements!

## License

**MIT Licance**

## Contact
You can get contact with Email (oguzkairakun@gmail.com)
