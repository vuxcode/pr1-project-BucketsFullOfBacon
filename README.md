[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-8d59dc4de5201274e310e4c54b9627a8934c3b88527886e3b421487c677d23eb.svg)](https://classroom.github.com/a/o-Yg1ufA)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-c66648af7eb3fe8bc4f294546bfd86ef473780cde1dea487d3c4ff354943c9ae.svg)](https://classroom.github.com/online_ide?assignment_repo_id=10647305&assignment_repo_type=AssignmentRepo)
# The Plan For My Programming Project

<!-- USE THIS TEMPLATE TO PLAN YOUR PROJECT - REMEMBER TO "COMMIT" YOUR CHANGES TO THIS FILE! FEEL FREE TO CHANGE ANYTHING OR ADD ANY SECTIONS THAT YOU NEED TO HELP YOU TO PLAN THE PROJECT -->

<!-- INSTRUCTIONS: https://vuxcode.netlify.app/new/pr1/lessons/major-project-brief/ -->

## Idea

My plan is to create a encryption program that will allow the user to iput text that will be encrypted using a displacementchipher technique. The user gets to input 
the ¨key¨ that the program uses to encrypt the text, after the user inputs the text and the key, the program will then encrypt the text and output it and the key used for the encryption to the user. The program will also have an option for the user to decrypt text that was encrypted using this program, in "decryption-mode" the program will ask for the encrypted text and the key that was used to encrypt it and then using both it will decrypt and display the text.
<!-- INSERT YOUR EXPLANATION FOR YOUR IDEA HERE -->

## Budget

2H: research, finding the types of commands that i need to use and simply figure out what way i want the program to find and "displace" the individual characters (including spaces and such).

15H: Desinging the encryption/decryption part of the program. This will without a doubt be the hardest part of the program but it is also the heart of the code, so i will budget alot of time to get it working.

4H: creating the "rest" of the program, the user interface, the option to choose between encryption or decryption and creating output format.

9H: reserv time/ improvment time, to act as a buffert if something takes longer then expected or time for me to add "nice to have" features that i come up with as write the code.

<!-- TRY TO BREAK YOUR IDEA DOWN INTO SMALLER PARTS AND GUESS HOW MUCH TIME EACH STEP WILL TAKE -->

## Sketches


![Plan](https://user-images.githubusercontent.com/129106031/228047098-a007eb46-6b11-4965-a42c-edd26c5a011a.png)



<!-- INSERT YOUR IMAGES IN THE REPOSITORY / OPTIONAL: COPY THE SYNTAX ABOVE TO ADD YOUR OWN IMAGES IN "MARKDOWN" -->

## Potential Problem List

1. Finding a good way for the program to find and "displace" the individual characters (including spaces and such) in such a way that it can be used en/decrypt the text using the same key.

<!-- WRITE A LIST OF PROBLEMS THAT YOU THINK YOU WILL HAVE TO TRY AND SOLVE DURING THE PROJECT -->

## Promises

1. The user will be able to encrypt or decrypt text with the program.
2. The program will use a displacement type chipher.

# Project Summary

This program encrypts or decrypts text using a simple displacement chipher.
When encrypting the program takes the inputed text then it converts the characters into ascii numbers and saves them in an array, then the program "encrypts" the text by adding the key to the numberical value of each character in the array. Then the program converts the ascii values back into characters and back into a string that then is displayd along with the key for the user.
The decrypting function functions in the same way, the only difference is what each variable is called and instead of adding the value of the key, the program removes the value of the key from each character value.

# User Guide

This program can encrypt text that you input into it, and also decrypt text that was encrypted by it.

To use it:
1: Choose if you want to encrypt or decrypt text.
2: Enter the text to be encrypted or decrypted.
3: Enter the key, if you are encrypting make up a number, it can be any number that is either possitive or negative as long as it is not 0.
If decrypting enter the key that was used to encrypt the text.
