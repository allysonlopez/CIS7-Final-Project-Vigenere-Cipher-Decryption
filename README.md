# CIS7-Final-Project-Vigenere-Cipher-Decryption
This repository is for the final project of CIS7 Fall 2024 

Allyson A Lopez
December 12, 2024

General decription and programming apporaches:
- The program will receive input from the user, if the user chooses to encrypt or decrypt the chosen word or phrase (with no space) and later a key, the code will then match the size of the word or phrase with a loop that iterates through each character of the word. Then modulo 26 is there to limit the values to only be in the range of the uppercase letters, if the user inputs a lowercase word or phrase the code will take it and covert it into uppercase to be able to encrypt and decrypt successfully. Both functions of encryption and decryption have similar methods encryption does forwards while decryptions follow the same but backwards. The code will follow the ASCII values to encrypt and decrypt the word or phrases used.

How to use the program: 
- The objective of the program is to successfully encrypt and/or decrypt the chosen word or phrase of the user, with the limitation of the use of spaces, symbols and numbers. The program is able to do the encryption and decryption process using the Vigenere Ciphe method, this process can also be done manually using the Vigenère square or Vigenère table. Starting up the program the user is prompted to choose 3 options with the use of a switch case, encryption, decryption or to quit the program. Encryption and Decryption being similar in the sense that the user will be prompted to unput their word or phrase of choice and that will be stored, it will then ask for a key. Depending on encryption or decryption the program will do the choice. If the user enters characters that are not valid to the program the program will not end or stop working rather it will simply display an error message and prompt the user to try again. If the user chooses the third option of quitting the program will display a message and ending the program. 
