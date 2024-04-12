
# 📚  Dictionary 📖

This Python application allows users to look up the meanings of words from a dictionary stored in a JSON file. It uses the `json` module to load the dictionary data and the `difflib` module to suggest close matches for misspelled words.

## 💻 Modules Used

- `json`: For loading the dictionary data from a JSON file.
- `difflib.get_close_matches`: For finding close matches for misspelled words.

## 🚀 How to Use

1. Ensure you have Python installed on your system.
2. Download the `data.json` file, which contains the dictionary data in JSON format.
3. Run the `dictionary.py` file in a Python environment.
4. Enter a word when prompted to search for its meaning.
5. If the word is found in the dictionary, the application will display its meaning(s). If not, it will suggest a close match if available.

## 📝 Application Logic

1. The application loads the dictionary data from the `data.json` file into a Python dictionary.
2. The `translate` function is used to look up the meaning of a word.
3. If the exact word is found in the dictionary, its meaning is returned.
4. If the word is not found but a close match is found, the application suggests the close match and asks the user if they meant that word.
5. If the user confirms, the meaning of the suggested word is returned. If not, an error message is displayed.
6. If the word is not found and no close match is found, an error message is displayed.

## 📋 Sample Output
![image](https://github.com/dharshii-22/PYTHON_MINI_PROJECTS/assets/110839215/706de608-a00f-4521-9496-11aceeb65011)

