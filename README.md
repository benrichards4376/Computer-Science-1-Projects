# Computer-Science-1-Projects
This contains descriptions of projects I completed while taking Computer Science 1 at UCF. My instructor, Dr. Szumlanski has instructed to not share any code from his projects. I have a private repository containing all the code, which I am allowed to share with potential employers, but cannot be made public for the aforementioned reason. This repo does have code I created from scratch while learning the class, just not the actual assignments.

Numeronym- print a sentence given the following rules:
 -if a word is shorter than 5 characters, print as normal.
 -otherwise, print the first and last characters, and in between, print the number of characters remaining in the word.
 -ex: Internationally would become I13y.
 
LonelyPartyArray- Let's say you had to store the frequency of test scores in an array. You would allocate an integer array of size 100 and increment the frequency at the cell, using the score as the index. This wastes space as the scores may not be evenly distributed (i.e. if all the scores are above a 50%, index 0-49 would be empty and take up space). The LonelyPartyArray, or LPA, prevents this by only allocating fragments of arrays, keeping track of what is active or inactive and freeing memory as cells become unused or fragments become empty.

ListyString- Reads a string from a file and creates a linked list that represents that string. Then, reads instructions from the same file to manipulate the string in a variety of the following ways:
 - replace all instances of a given substring from within the string, with a given key
 - concatenate a string to the working string
 - prepend a string to the working string
 - reverse the working string
 - censor by replacing all occurences of a given substring with the char '*'
 - delete all instances of a given substring in the working string
 - interweave a string into the working string (interweaving "key" into "str" would yield "ksetyr")
 - interweave a ListyString into another
 - print the number of times a given key occurs in the working string
 - print the working string
 - compare two ListyStrings like strcmp in string.h

KindredSpirits- Creates binary trees and implements the following comparison functions:
 - checks if two binary trees are reflections of one another (mirrored)
 - given one binary tree, constructs a reflection of that tree
 - determines if two trees are "KindredSpirits". Two trees are kindred spirits if the pre-order traversal of one tree is equal to the post-order traversal of the other or vice-versa.

TriePrediction- Reads a corpus file (text document) and creates a trie representing all the words in that file. Each Trie node has a subtrie that stores all the words that directly follow it in the corpus, then reads a separate file with instructions to perform a variety of the following tasks:
 - prints the trie in its entirety, including the subtries in each node
 - Simulates text prediction by printing the word that most commonly follows the given word, then does the same for that word and so forth, a given number of times.
 - gets the most frequently occuring word in the trie and copies it into a string
 - counts how many words begin with a given prefix
 - counts how many new nodes would need to be created in order to insert a given word into the trie.


