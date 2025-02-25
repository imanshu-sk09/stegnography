## Image-Based Steganography for Secure Message Hiding

## Project Description

This project demonstrates steganography, a technique for hiding secret messages inside images without altering their visible appearance. The message is encrypted and can only be retrieved with a correct password, ensuring secure and covert communication.

## Features

* Message Encryption: Embed a secret message inside an image.

* Password Protection: Only users with the correct password can decrypt the message.

* Image-Based Security: The message remains hidden without noticeable changes in the image.

* Cross-Platform Compatibility: Works on Windows, macOS, and Linux.

## Technology Stack

* Programming Language: Python

## Libraries Used:

* OpenCV (cv2) – for image processing

OS – for file handling

String Manipulation – for encoding/decoding text

## Installation & Setup

* Prerequisites

Ensure you have Python installed. Then, install the required dependencies using:

pip install opencv-python

Usage Instructions

## Run the Script:

python stegno.py

Enter the Secret Message to be hidden inside the image.

Set a Password for encryption.

View the Encrypted Image (Saved as Encryptedmsg.jpg).

Decrypt the Image: Run the script again and enter the correct password to reveal the hidden message.

Example Output

Enter secret message: Hello World
Enter password: mypass123
Encrypted Image saved as 'Encryptedmsg.jpg'

Enter passcode for Decryption: mypass123
Decryption message: Hello World

Future Enhancements

Implement stronger encryption before embedding the text.

Support multiple image formats (PNG, BMP, GIF).

Develop a GUI for non-technical users.

GitHub Repository

https://github.com/imanshu-sk09/stegnography

License

This project is open-source and available under the MIT License.

Contributors

Himanshu Sonkar

For any issues or suggestions, feel free to open an issue on GitHub.

