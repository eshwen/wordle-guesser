# wordle-guesser

Guess answers to Wordle and its variants.

## Rough plan

0. Scrape all 5 letter words from a given dictionary
1. Connect to Wordle game
2. Decide on a starting word
    1. Could be chosen by user
    2. Could be randomly generated from a possible set of words
    3. Could have an algorithm to choose the most optimal starting word
3. Input the word and scrape the result
4. Use the result to filter remaining words in dictionary
5. Choose the optimal word for the next guess (same algorithm as 2.3?)
6. Repeat steps 3-5
