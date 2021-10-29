# Mobile-Device-Keyboard
This program implements a trie in order to suggest words for auto-complete once given a sentence to train and a key to look for.

A trie is a tree-base structure that runs in O(M) time where M is the maximum string length. A drawback is the space complexity, where each letter can have children proportional to all letters of the alphabet, or even more if special characters or numbers are used.

I decided to leave in special characters because it allows us to autocomplete things like websites (using periods), numbers, and punctuation.


To test, input the sentence to be trained within the driver portion of the code in quotation marks and the key to look for:

sentence = "INPUT SENTENCE HERE"

keys = sentence.split()

key = "INPUT KEY TO SEARCH HERE"

Alternatively, this section may be commented out, and the section below it marked by "#Alternatively, we can test custom input from the user here:" may be uncommented if the user would like to input a custom sentence and key in the command line interface.

Testing was done by running the program using the command line interface on a linux machine.
