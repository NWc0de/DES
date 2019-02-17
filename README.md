# DES
Implementation of DES and triple DES in Python. Operates on files. 

This implementation uses the PKCS5 padding scheme and strips the padding with regex.
I am not sure if this will conflict with files that potentially have a similar byte sequence.

The key is alphanumerical string translated into integer form.

Thanks for checking my program out. Input and improvements are appreciated.

On a final note, I realize DES in ECB mode has some security flaws. This was mainly meant to be
a learning experience and I thought it might be helpful to share for others who hope to learn about
block ciphers. 
