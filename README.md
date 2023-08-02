# Ceasar-Chipher-Pyscript

## Introduction

This is a web-based tool that allows you to encrypt and decrypt messages using the Caesar Cipher algorithm. It provides a user-friendly interface where you can enter a text, choose whether to encrypt or decrypt, and see the corresponding output.

## How to Use

1. Open the `index.html` file in your web browser. The web page will load, and you'll see two text input fields along with two buttons: one for encryption and another for decryption.

2. **For Encryption:**
   - Enter the text you want to encrypt in the "For Encryption" input field.
   - Click the "OK" button under the "For Encryption" section.
   - The encrypted output will be displayed in the adjacent div with a palevioletred border.

3. **For Decryption:**
   - Enter the text you want to decrypt in the "For Decryption" input field.
   - Click the "OK" button under the "For Decryption" section.
   - The decrypted output will be displayed in the adjacent div with a palevioletred border.

## Caesar Cipher Algorithm

The Caesar Cipher is a substitution cipher that shifts characters in the input text by a fixed number of positions in the alphabet. In this tool, the encryption shifts letters 4 positions forward (wrapping around the alphabet), while the decryption shifts letters 4 positions backward to revert the encryption.

The algorithm handles both uppercase and lowercase letters while preserving other characters unchanged.

## Dependencies

The tool relies on the [PyScript](https://pyscript.net) library to enable the Python code to interact with JavaScript. The necessary scripts are included in the `index.html` file, so there's no need for additional installations.

## Note

Please note that this tool is a simple demonstration of the Caesar Cipher algorithm and is not meant for robust cryptographic purposes. The Caesar Cipher is a relatively weak encryption method and can be easily cracked with modern cryptographic techniques.
