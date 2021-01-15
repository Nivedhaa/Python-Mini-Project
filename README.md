# <b>Python-Mini-Project</b>

# <b>Problem 1:</b>
Write a program to calculate area of shapes. Your program should be capable of calculating the area of a square, rectangle, triangle and a circle. The user should be presented with options to select the shape. Based on which shape is chosed by the user, the program should ask for the appropriate input and print the resulting area on the screen.
When the program is run, the screen should display something like this:<br>

Which shape would you like to calculate the area for? Please enter the option number-<<br>
1. Square<br>
2. Rectangle<br>
3. Triangle<br>
4. Circle<br>
Enter Option: _<br>

Say the user enters the option 1.<br>

Please enter the length of a side: _<br>

If the user enters a value of 5. The output should be:<br>

The area of the square is 25<br>

This program should indicate that the input is invalid if the user enters a character instead of a number as input. For instance if the user enters a value of ‘a’ instead of 5 in the previous example the program should prompt:<br>

Invalid input, please enter a number: _

# <b>Problem 2:</b>

Create and encrypter in python based on the ceaser cipher. It is a substitution cipher where each character of the original text is shifted a certain number characters in the alphabet. Write a function that would require 2 arguments – the input text to be encrypted and a key. For eg: Given the input text ‘hello’ and the key 3, the resulting encryted text would be ‘khoor’. Here you can see that every character in the string hello is shifted by 3 characters. ‘h’ has shifted to ‘k’, ‘e’ has shifted to ‘h’ and so on. If a key of 5 were used, the resulting string would be ‘mjqqt’. This function should be capable of ignoring any characters which are not alphabets. Th2 character ‘z’ entered b y the user for a key of 3 would result in ‘c’.<br>

Usage:<br>
encrypt(‘hello world!’, 3)<br>
‘khoor zruog!’<br>

Similarly create decrypter which can decode the encryted text when provided the input text and key<br>

Usage:<br>
decrypt(‘khoor zruog!’, 3)<br>
‘hello world!’<br>

For the sake of simplicity you can assume that input solely consists of lowercase alphabets, spaces and punctuation symbols. Numbers in the input text would also be ignored similar to symbols.

# PANDAS MINIPROJECT
Analysis on IPL dataset
