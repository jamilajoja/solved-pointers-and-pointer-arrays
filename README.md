Download Link: https://assignmentchef.com/product/solved-pointers-and-pointer-arrays
<br>
Write a program to read in a phrase from the keyboard, re-display the text, and display a message

on the following line giving the text’s status as a palindrome. Do not use any arrays or subscripting

in this program, except for arrays of pointers.

A palindrome is a word or phrase which is the same backwards as forwards;

for example “civic”, “toot”, and “radar” are palindrome words; each word is spelled the same

left to right, as right to left.

“A man, a plan, a canal – Panama!” is a palindrome phrase; ignoring case, spaces and punctuation,

the phrase is spelled the same left to right, as right to left.

Part I

Determine if the phrase entered by the user is a palidrome. Setting a pointer to the first character

in the entered text, and another pointer to the last character, move the pointers toward the center

comparing the characters. Skip over anything that isn’t a letter. If the pointers meet before finding

any differences, you have a palindrome. Display a message to that effect on the next console line.

Part II

A word is defined to be any sequence of upper or lower case letters, but not numbers or punctuation.

White space separates words. There may not be any white space in front of the first word in your text,

or following the last word. You may assume that words are not hyphenated or otherwise carried across

line boundaries. For this problem there is no minimum word size for palindromes, for example all

single letter words would be considered word palindromes. Using pointers, search each word in the entered

text, and display a count of the palindromes found.

Example output:

Enter some text:O’Reiley’s Honda Civic is not a level, nor straight car.

Phrase is NOT a palindrome. 3 word palindromes found. [note: the 3 words are “Civic”, “a” and “level”]