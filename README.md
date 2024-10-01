# PRODIGY_CS_02
This Python script offers a basic approach for encrypting and decrypting images using an XOR operation. It secures image files by modifying their pixel values based on a user-defined encryption key.

How It Works:
Encryption: Each pixel's RGB values are altered through an XOR operation with a given key (an integer between 0 and 255).
Decryption: The same XOR operation is used on the encrypted image with the same key to revert it to its original form.
Usage:
Enter the encryption key: Provide a number between 0 and 255 to modify the pixel values.
Select mode: Choose 'encrypt' to secure the image or 'decrypt' to restore the original image.
Provide image paths: Input the file paths for the source image and specify where the output image will be saved.
Requirements:
PIL (Python Imaging Library): Install by running pip install Pillow.
While this script is useful for simple image encryption tasks, it’s not recommended for secure applications due to the basic nature of XOR encryption.
