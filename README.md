# Pig Latin Translator

This Python script translates English messages into Pig Latin. It processes each word individually, handles non-letter characters, and maintains the original casing of the words.

## Usage

1. Run the script.
2. Enter the English message you want to translate.
3. The script will output the message translated into Pig Latin.


## Example

```
Enter the English message to translate into Pig Latin: 
Hello, world!
Ellohay, orldway!
```

## Code Explanation

- **Input Handling**: Prompts the user to enter an English message.
- **Vowels Definition**: Defines a tuple `VOWELS` containing vowel characters.
- **Translation Process**:
  - Splits the message into words.
  - Separates non-letter characters at the beginning and end of each word.
  - Checks the original casing of the word.
  - Converts the word to lowercase for processing.
  - Moves initial consonants to the end and appends 'ay', or appends 'yay' if the word starts with a vowel.
  - Restores the original casing.
  - Reattaches any separated non-letter characters.
- **Output**: Joins the translated words back into a single string and prints the Pig Latin message.
