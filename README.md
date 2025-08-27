# Programming Assignment 1
#### Deadline: August 27, 2025
## I. Intended Learning Outcomes:
  1. To identify the basic codes and functions in Python Programming
  2. To be able to apply the different codes and functions in creating a Python program.
## II. Instructions:
  Write a Python script/code in the Jupyter Notebook to do the given problems. You may submit your Jupyter notebook in the dedicated submission bin.
## III. Problems:
  #### 1.) ALPHABET SOUP PROBLEM: 
  Create a function that takes a string and returns a string with its letters.
  #### 2.) EMOTICON PROBLEM: 
  Create a function that changes specific words into emoticons. Given a sentence as a string, replace the words smile, grin, sad and mad with their corresponding emoticon.
  #### 3.) UNPACKING LIST PROBLEM: 
  Unpack the list writeyourcodehere into three variables, being first, middle, and last, with middle being everything in between the first and last element. Then print all three variables.
## IV. Answers and Explanation:
### ALPHABET SOUP PROBLEM
<img width="559" height="317" alt="Image" src="https://github.com/user-attachments/assets/28855da7-2d26-4d2c-b43c-7e98a4330fbf" />

The function "alphabet_soup(word)" takes a word as input. Inside the function, the first line turns the word into a list of letters using "list(word)". This is done because individual letters in a list can be sorted, while strings cannot. Next, "letters.sort()" is the most imortan part of the code because this line of the code is what arranges the letters in alphabetical order. After sorting, the function uses """.join(letters)" to put the letters back together into a single word. This joined word is then returned as the final result. For example, if the input is "hello", the function will return "ehllo" as shown in the output.
### EMOTICON PROBLEM
<img width="668" height="601" alt="Image" src="https://github.com/user-attachments/assets/8246c81f-83d2-4ae9-8c18-6f4d9d9603b5" />

The "emoticon(sentence)" function starts by creating a dictionary named d that matches certain words like "smile", "grin", "sad", and "mad" to their corresponding emoticons like ":)", ":D", ":(", and ">:(". Then, the sentence is split into individual words using the "split()" function, so each word can be checked separately. An empty list called "new_words" is created to store the updated words or emoticons. The function then goes through each word in the sentence using a for loop. Inside the loop, each word is changed to lowercase with "lower()" so that it matches the dictionary keys even if the original word has uppercase letters. If the lowercase word is found in the dictionary, the matching emoticon is added to the "new_words" list. If not, the original word is added instead. After going through all the words, the list "new_words" is joined back into a full sentence using "" ".join(new_words)", and this final sentence is returned. For example, if the input is "I am mad", the output will be "I am >:(" as shown in the output.
### UNPACKING LIST PROBLEM
<img width="490" height="399" alt="Image" src="https://github.com/user-attachments/assets/cb202d38-cbce-4a1e-ae94-a0b7e9904e22" />

In the last problem, a list of numbers from 1 to 6 is created using "list = [1, 2, 3, 4, 5, 6]". The code then outputs 3 different parts of the list. First, it stores the first number in a variable called "first" by using "list[0]". Then, it creates a new variable called "middle" that contains all the numbers between the first and the last using slicing: list[1:-1]. Lastly, the last number in the list is stored in a variable called "last" using "list[-1]", which means the last element. These three variables now hold the first, middle, and last parts of the list. For this example, first is 1, middle is [2, 3, 4, 5], and last is 6 as shown in the output.
