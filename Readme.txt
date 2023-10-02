In summary, this program reads a user-input sentence character by character, calculates its length, counts the number of words, and identifies the number of vowel characters, presenting these results to the user. Initializes three variables to calculate:

The length of the sentence (the number of characters).
The number of words in the sentence (assuming words are separated by a single space).
The number of vowel characters (assuming lowercase vowels) in the sentence.
Asks the user to input a sentence that must end with a period.

Iterates through each character in the input sentence and does the following:

Increases the sentenceLength variable by one for each character, calculating the total length of the sentence.
If a space character is encountered, it increases the wordCount variable by one, assuming that spaces separate words.
If a vowel character ('a', 'e', 'i', 'o', 'u') is found, it increments the vowelCount variable.
Adds 1 to wordCount at the end to account for the last word.

Displays the results to the user, including the sentence's length (number of characters), the number of words in the sentence, and the number of vowel characters in the sentence