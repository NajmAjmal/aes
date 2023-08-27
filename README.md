# AES Encryption and Decryption Tool

This tool provides a simple web interface to encrypt and decrypt sensitive data using the AES encryption algorithm. It utilizes the CryptoJS library to perform AES encryption and decryption operations in your browser.

## Features

- Encrypt text using AES encryption algorithm
- Decrypt encrypted text using AES decryption algorithm
- Web-based user interface for ease of use
- Password-based encryption and decryption

## How to Use

1. **Access the Tool**: Open the `index.html` file in a web browser to access the AES Encryption and Decryption Tool.

2. **Enter Text and Password**: On the web interface, you'll find input fields to enter the text you want to encrypt or decrypt and the password to use for encryption/decryption.

3. **Choose Action**: Click on the "Encrypt" button to encrypt the entered text or click on the "Decrypt" button to decrypt the entered text.

4. **View Results**: The encrypted or decrypted result will be displayed in the result area below the buttons.

## Parameters

The AES Encryption and Decryption Tool supports the following URL parameters:

- `action`: Specifies the action to perform. Use `encrypt` to encrypt the text and `decrypt` to decrypt the text.
- `text`: The text you want to encrypt or decrypt, enclosed in double quotes.
- `password`: The password used for encryption or decryption, enclosed in double quotes.

Example URLs:
- Encrypt: `https://yourdomain.com/aes/index.html?action=encrypt&text="Your_Text_Here"&password="Your_Password_Here"`
- Decrypt: `https://yourdomain.com/aes/index.html?action=decrypt&text="Encrypted_Text_Here"&password="Your_Password_Here"`

View live example [here](https://github.com/NajmAjmal/aes)

## Credits

This tool utilizes the CryptoJS library for AES encryption and decryption operations. It was developed by Najm Ajmal.

## License

This project is licensed under the [MIT License](LICENSE).
