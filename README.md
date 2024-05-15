This Python script is a simple word guessing game. It downloads a list of words and hints from a public GitHub repository, 
randomly chooses a secret word, displays a hint to the user, and asks the user to guess the word. If the user gets it right,
a congratulations message is displayed; otherwise, the correct word is revealed.

Functionalities
<br>

Importing Libraries:

requests: To make HTTP requests and download the list of words.
random: To select a random word from the list.
<br>

Download the Word List:

The URL pointing to a JSON file containing words and hints is defined.
An HTTP GET request is made to download the JSON file.
The content of the JSON file is loaded into a data variable.
<br>

Secret Word Selection:

A word is randomly selected from the list.
The secret word and its associated hint are extracted.
<br>

User Interaction:

The number of letters in the secret word and the hint are displayed.
The user is asked to guess the word.
The user's response is compared with the secret word:
If the answer is correct, a success message is displayed.
If the answer is incorrect, the correct word is revealed.



Examples:


