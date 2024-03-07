# Fantrordle

A daily fantroll name guessing game, made with React. Originally by [https://github.com/cwackerfuss](cwackerfuss), but that repository no longer exists.

## Build and run

### To Run Locally:

Clone the repository and perform the following command line actions:

```bash
$> cd [project_directory]
$> npm install
$> npm run start
```

[http://localhost](http://localhost) should automatically open in your browser.

## FAQ

### How can I change the length of a guess?

- Update the `MAX_WORD_LENGTH` variable in [src/constants/settings.ts](src/constants/settings.ts) to the desired length.
- Update the `WORDS` array in [src/constants/wordlist.ts](src/constants/wordlist.ts) to only include words of the new length.
- Update the `VALID_GUESSES` array in [src/constants/validGuesses.ts](src/constants/validGuesses.ts) arrays to only include words of the new length.