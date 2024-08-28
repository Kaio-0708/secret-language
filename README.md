
# 🕹️ Secret Language

This Python script is a simple word guessing game. It downloads a list of words and hints from a public GitHub repository, randomly chooses a secret word, displays a hint to the user, and asks the user to guess the word. If the user gets it right, a congratulations message is displayed; otherwise, the correct word is revealed.

## 🎮 Functionalities

### Importing Libraries

- **requests**: To make HTTP requests and download the list of words.
- **random**: To select a random word from the list.

### Download the Word List

- The URL pointing to a JSON file containing words and hints is defined.
- An HTTP GET request is made to download the JSON file.
- The content of the JSON file is loaded into a data variable.

### Secret Word Selection

- A word is randomly selected from the list.
- The secret word and its associated hint are extracted.

### User Interaction

- The number of letters in the secret word and the hint are displayed.
- The user is asked to guess the word.
- The user's response is compared with the secret word:
  - If the answer is correct, a success message is displayed.
  - If the answer is incorrect, the correct word is revealed.

### Usage example

![Captura de tela 2024-05-15 155911](https://github.com/Kaio-0708/secret-language/assets/123708201/f00c0c28-6c06-4994-845f-4b4ddb0be06e)
![Captura de tela 2024-05-15 160056](https://github.com/Kaio-0708/secret-language/assets/123708201/4cc0bcc9-0686-4a0c-ad00-1c1103a13c7d)

## Autor

Kaio Vitor - [GitHub](https://github.com/Kaio-0708)
