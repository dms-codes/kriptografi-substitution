# Simple Substitution Cipher

This Python script demonstrates a simple substitution cipher. It allows you to encrypt and decrypt text using a custom cipher alphabet.

## Overview

A substitution cipher is a method of encrypting plaintext by replacing each letter with another letter. In this script, you can specify a custom cipher alphabet to perform both encryption and decryption.

- The `plaintext` variable contains the text that you want to encrypt.
- The `cipheralphabet` variable contains the custom substitution alphabet.
- The `plainalphabet` variable contains the standard uppercase alphabet.

The script provides two main functions:

- `encrypt(plaintext, cipheralphabet)`: Encrypts the input `plaintext` using the specified `cipheralphabet` and returns the ciphertext.
- `decrypt(ciphertext, cipheralphabet)`: Decrypts the input `ciphertext` using the specified `cipheralphabet` and returns the original plaintext.

## Usage

1. Customize the `plaintext` and `cipheralphabet` variables in the script to set your desired input text and custom substitution alphabet.

2. Run the script by executing the following command in your terminal:

   ```bash
   python your_script_name.py
   ```

3. The script will perform the encryption and decryption using the specified inputs and print the results.

4. You can modify the `plaintext` and `cipheralphabet` variables in the script to test different inputs and substitution alphabets.

## Example

Suppose you have configured the script with the following settings:

- `plaintext = 'SELAMAT DATANG DI KELAS KRIPTOGRAFI'`
- `cipheralphabet = 'QAMOCDBHRUWLKJNVTZFISPEGYX'`

After running the script, you will see the ciphertext and the decrypted plaintext as output.

## Security Note

This is a simple example of a substitution cipher and should not be used for secure encryption. In practice, more complex encryption algorithms and key management are required for secure communication.

## License

This script is provided under the [MIT License](LICENSE).
```

Replace `"your_script_name.py"` with the actual name of your script. Customize the README.md file further if needed to include additional information or usage examples for your project.
