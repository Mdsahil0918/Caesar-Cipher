# Caesar-Cipher
Here's a README file highlighting the tools and modules used in your Caesar cipher program:

---

# Caesar Cipher Program

## Overview

This program implements a Caesar cipher, a type of substitution cipher in which each letter in the plaintext is shifted a certain number of places down or up the alphabet. The program allows users to encode or decode messages based on the Caesar cipher technique. It also includes options for restarting the program and handling shifts greater than the number of letters in the alphabet.

## Tools and Modules Used

### Programming Language
- **Python**: The programming language used for implementing the Caesar cipher.

### Libraries and Modules

- **art**: 
  - A custom module (`art.py`) that provides the logo art to be printed when the program starts. Ensure that this module is available in the same directory as your script for it to function properly.

## How to Run

1. **Ensure `art.py` is Available**:
   - Make sure the `art.py` file is present in the same directory as the script. This file should contain the ASCII art logo used in the program.

2. **Run the Script**:
   - Execute the script using Python:
     ```sh
     python script_name.py
     ```

3. **Interacting with the Program**:
   - Follow the prompts to encode or decode a message by entering the desired direction, message text, and shift number.
   - If you wish to restart the cipher program, type 'yes' when prompted. If you prefer to exit, type 'no'.

## Code Details

- **`alphabet` List**: 
  - Contains all lowercase letters of the English alphabet, repeated to handle shifts that wrap around the end of the list.

- **`caesar` Function**: 
  - Takes `start_text`, `shift_amount`, and `cipher_direction` as arguments. It performs the Caesar cipher encoding or decoding based on the specified direction and shift amount.

- **Shift Handling**: 
  - Shift values are adjusted using modulus operation to ensure they remain within the bounds of the alphabet.

- **User Interaction**: 
  - Users are prompted to input their choice for encoding or decoding, the message, and the shift value. They can also choose to restart the program or exit.

