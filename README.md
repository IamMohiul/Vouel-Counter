# Vowel Checker Application

A simple JavaScript application that counts the number of vowels in a given text.

## Table of Contents

- [Features](#features)
- [Usage](#usage)
- [How it Works](#how-it-works)
- [License](#license)

## Features

- Counts the number of vowels (a, e, i, o, u) in a given text.
- User-friendly interface with a textarea for input and a button to trigger the vowel count.
- Displays the total number of vowels in the result.

## Usage

1. Clone the repository:

   `git clone https://github.com/IamMohiul/Vouel-Counte.git`
2. Open the index.html file in your web browser.
3. Enter the desired text in the textarea.
4. Click the "Count Vowel" button to see the total number of vowels in the input text.

## How it Works
The application uses JavaScript to iterate through each character in the input text, checking if it is a vowel using the isVowel function. The count is then displayed to the user.

The `isVowel` function checks if a given character is a vowel by comparing it against an array of vowels `(["a", "e", "i", "o", "u"])`.
