# Playfair
Jerry Haynes
CS 408 – Applied Cryptography
September 21, 2017 

What is a Playfair Cipher?
This cipher was one of the first practical digraphs substitution ciphers. This cipher was designed by a man that went by the name of Charles Wheatstone. During that time, it was incredible hard to break do to the amount of combinations that can be created during its use.

Rules of the Playfair cipher:
1.	Letters that are the same pair must be separated by the letter X.
2.	Two PT letters that are in the same row of the matrix are each replaced by the letter to the right, with the first element of the row circularly following the last. 
3.	Two PT letters that are in the same column are each replaced by the letter under, with the top element of the column circularly following the last.
4.	 each plaintext letter in a pair is replaced by the letter that lies in its own row and the column occupied by the other plaintext letter.

Technology: Python



The strip of code

 above is the function created to grab the key from the user. This is done by creating a simple nested for loop. Due to the I and J having to be the same body it made things slightly complex.


The code above was the encryption code I designed. This was probably the most complex part due to the amount of matrix’s that was in the code. I had to make the for loop nested with an if loop. The reason for this is for the code to follow the rules of the playfair cipher. The code runs through every line to match up the letters to make the imaginary boxes to encrypt. 

To test I used my code. (I only used this but its open for any word you choose to use)
Key: Unfair
Message: Balloon





