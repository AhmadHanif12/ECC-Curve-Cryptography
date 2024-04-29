
# ECC Operations Tool README

This Python script provides a command-line interface to perform various operations related to Elliptic Curve Cryptography (ECC). The tool allows you to verify elliptic curves, check if points lie on a given curve, perform ECC-based Diffie-Hellman key exchange, and perform ECC encryption/decryption.

## Prerequisites

Before running the script, ensure you have Python installed on your system. This script was tested with Python 3.8 and above.

## How to Run the Script

1. Save the script in a file named `ECC.py`.
2. Open your command line interface (CLI).
3. Navigate to the directory where you saved `ECC.py`.
4. Run the script using Python by typing:
   ```
   python ECC.py
   ```

## Navigating the Menu

Once the script is running, you will be presented with a menu of options:

1. **Verify Elliptic Curve**: Check whether the specified elliptic curve parameters define a valid curve.
2. **Check if Point is on Curve**: Determine if a given point (x, y) lies on the specified elliptic curve.
3. **ECC-based Diffie-Hellman**: Perform a Diffie-Hellman key exchange using elliptic curve cryptography.
4. **ECC Encryption/Decryption**: Encrypt and decrypt messages using elliptic curve cryptography.
5. **Exit**: Exit the program.

### Menu Options Detailed

- **Option 1**: Enter the curve parameters \(a\) and \(b\), and optionally the modulus \(n\) if you are working with a curve over a finite field.
- **Option 2**: Provide the point coordinates \(x\) and \(y\) along with the curve parameters to check if the point is on the curve.
- **Option 3**: Execute an ECC-based Diffie-Hellman exchange. You will need to input the curve parameters, generator point coordinates, and private keys for both parties.
- **Option 4**: For encryption, input the public key, generator point, message point, and a random integer \(k\). For decryption, input the receiver's private key.
- **Option 5**: Use this option to cleanly exit the program.

## Notes

- Make sure to enter all inputs as integers unless specified otherwise.
- When entering the modulus \(n\), press enter without typing anything to skip and perform calculations in real numbers.

Enjoy using the ECC Operations Tool for your cryptographic needs!
