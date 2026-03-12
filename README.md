#steganography-c
Image steganography in C using LSB technique for secure encoding and decoding of secret data in BMP files.

#Features
Hide secret messages in images (Encoding)
Extract hidden messages from images (Decoding)
Supports BMP images
User-friendly command-line interface
Sample images included for testing (beautiful.bmp)
#How to Run
1.Clone the repository:
git clone https://github.com/sadvika-ch/steganography-c.git
cd steganography
2. Compile the program
gcc src/steganography.c -o steganography
3. How to run
Encode ./steganography -e beautiful.bmp secret.txt <output.bmp>(optional)

Decode ./steganography -d output.bmp <output.txt>(optional)

Use -e to encode information

Use -d to decode information

#Notes
Follow the prompts to enter the BMP file path and view its metadata.
A sample BMP file (beautiful.bmp) is included for testing.
During encoding, a temporary file is used to avoid disturbing the original file.
After encoding, the temporary file is decoded to see the encoded data.
Skills Learned
C Programming: File handling, structures,Bitwise Operators and pointers Binary Data Processing: Reading and interpreting BMP files Multimedia File Handling: Understanding BMP image structure and LSB steganography

#Dependencies
GCC or any C compiler



