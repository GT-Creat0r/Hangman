# Hangman Game

A simple Hangman game built using React and TypeScript.

## Features
- Interactive keyboard for letter guessing
- Hangman drawing updates based on incorrect guesses
- Win and lose detection
- Restart functionality using the "Enter" key

## Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/hangman-game.git
   ```
2. Navigate into the project directory:
   ```sh
   cd hangman-game
   ```
3. Install dependencies:
   ```sh
   npm install
   ```
4. Start the development server:
   ```sh
   npm start
   ```

## How to Play
- Press any letter key to guess a letter.
- If the guessed letter is in the word, it will be revealed.
- If the guessed letter is incorrect, a part of the hangman drawing will appear.
- You lose after 6 incorrect guesses.
- You win if you guess all letters correctly.
- Press "Enter" to restart the game.

## File Structure
```
/
├── src/
│   ├── components/
│   │   ├── HangmanDrawing.tsx
│   │   ├── HangmanWord.tsx
│   │   ├── Keyboard.tsx
│   ├── wordList.json
│   ├── App.tsx
│   ├── index.tsx
├── package.json
├── README.md
```

## Future Enhancements
- Add difficulty levels
- Implement a scoring system
- Improve UI with animations and styling

## License
This project is open-source and available under the [MIT License](LICENSE).

