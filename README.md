# PYTHON_01

This Python program implements the Caesar Cipher algorithm for encrypting and decrypting text messages. It allows users to input a message and a shift value to perform encryption and decryption.

## Usage

1. Run the program:
  
   python caesar_cipher.py
   
2. Choose the operation mode:
   - Enter 'e' for encryption
   - Enter 'd' for decryption
   - Enter 'q' to quit the program

3. If you chose 'e' or 'd', follow these steps:
   - Enter the message you want to encrypt or decrypt
   - Enter a shift value between 1 and 25

4. The program will display the result (encrypted or decrypted message)

5. The program will then return to step 2, allowing you to perform another operation or quit

## Example

`
Enter 'e' for encrypt, 'd' for decrypt, or 'q' to quit: e
Enter the message: Hello, World!
Enter the shift value (1-25): 3
Encrypted message: Khoor, Zruog!

Enter 'e' for encrypt, 'd' for decrypt, or 'q' to quit: d
Enter the message: Khoor, Zruog!
Enter the shift value (1-25): 3
Decrypted message: Hello, World!

Enter 'e' for encrypt, 'd' for decrypt, or 'q' to quit: q
Goodbye!
