<p align="center">
  <img src="https://img.icons8.com/cute-clipart/256/spellcheck.png" width="128" />
  <h1 align="center">📚 WAGNER-FISCHER 🖋️</h1>
  <p align="center">
    <em>🔍 Spell checker based on the Wagner-Fischer¹ distance 📝</em>
  </p>
  <p align="center">
    <img src="https://img.shields.io/badge/Python-3776AB.svg?style=for-the-badge&logo=Python&logoColor=white" alt="Python">
  </p>
</p>

##### ¹ A measure of the minimum number of operations required to transform one word into another.

## 🎯 Features

- `load_dictionary(file_path: str) -> Generator[str, None, None]`: Load a dictionary of words from a file
- `wagner_fischer(word1: str, word2: str, threshold: int) -> float`: Calculate the Wagner-Fischer distance between two words
- `spell_check(word: str, dictionary: Generator[str, None, None], top: int, threshold: float) -> List[Tuple[str, float]]`: Check the spelling of a word and return the top suggestions based on the Wagner-Fischer distance
- `print_help()`: Print the help menu
- `print_settings()`: Print the settings menu
- `user_interface() -> None`: User interface to interact with the spell checker

## 🚀 Usage

To use the spell checker, simply run the Python script and follow the instructions in the console. You can check the spelling of a word, change the settings and load a different dictionary.

## 📜 Commands

- `check <word>`: Check the spelling of a word
- `settings`: Display the settings menu
- `help`: Display the help menu
- `bye`: Exit the program

### ⚙️ Command settings

- `dictionary <file_path>`: Load a different dictionary file
- `threshold <value>`: Set the maximum Wagner-Fischer distance for suggestions
- `top <number>`: Set the number of suggestions to display

## Credits

This project is a fork of the [original work](https://github.com/b001io/wagner-fischer) by [b001](https://github.com/b001io), inspired by his video ["The Algorithm Behind Spell Checkers"](https://www.youtube.com/watch?v=d-Eq6x1yssU) 🎥