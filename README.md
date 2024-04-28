Caesar Ciper 
The Caesar Cipher is a shift cipher and encrypts the data by replacing the original letters with those “x” number of characters ahead in the alphabet.
You can run the code by downloading the source file and running the program in the terminal or python editor.
***note if you get an error like this:
Traceback (most recent call last):
File "C:\caesarCipher.py", line 4, in <module>
import pyperclip
ImportError: No module named pyperclip

then you have not downloaded the pyperclip module, you can comment out the code on line 1 and 41
***note if you comment out the code on line 1 and 41 the encrypted or decrypted text won't be copied to the clipboard at the end of the program.
To decrypt the message, just paste the output text as the new value stored in the 'message' variable on line 4. Then change the assignment statement on line 9 to store the string 'decrypt' in the variable 'mode.
