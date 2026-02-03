# My self-made Python implementation of the RSA algorithm  

The script allows you to encrypt and decrypt a message using a pair of prime numbers.  

## Important clarification

The .exe file is in releases. This `.exe` file does not have viruses. It was created for convenience. I made this file thanks to `python -m PyInstaller --onefile ...`. If you do not trust the `.exe` file, I recommend you to use the `.py` file.

## Functionality

- Entering a message (English or Russian, you choose).  
- Conversion to numeric format.  
- Key generation (p, q, d, e).  
- Encryption and decryption.  
- Display of intermediate steps.  

## How does it work?

1. Open the `.exe` file or `.py` file.
2. You choose English or Russian. 1 or 2, respectively.
3. Write the message (one word). You can write uppercase and lowercase letters.
4. Choose the prime number p that you want.
5. Choose the prime number q that is greater than p.
Warning: this code doesn't accept a combination of (p;q), respectively: (2;3),(2;5),(2;7),(3;5). The program will ask you to choose other numbers.
6. The program calculates all the values using formulas and outputs an encrypted message and decrypts it at the same time.

## Important: This implementation is intended for educational purposes. Do not use it in production or in real security systems
