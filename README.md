# Mnemonica Stack Trainer

An interactive web application to help magicians learn and practice Juan Tamariz's Mnemonica stack order. This trainer allows users to practice memorizing both card positions and cards at specific positions.

## Features

- Two practice modes:
  - Card → Position: See a card, guess its position
  - Position → Card: See a position, guess the card
- Progressive difficulty levels:
  - First 10 cards
  - First 20 cards
  - First 30 cards
  - First 40 cards
  - Full deck (52 cards)
- Score tracking for correct and incorrect attempts
- Visual feedback for correct answers
- Mobile-responsive design

## Quick Start

The application is built with vanilla HTML, CSS, and React (via CDN), so it's very easy to run locally:

1. Clone the repository:

```bash
git clone https://github.com/yourusername/mnemonica-stack-trainer.git
cd mnemonica-stack-trainer
```

2. Serve the files using any local server. For example:

   - Using Python 3: `python -m http.server 8000`
   - Using Node.js's `serve`: `npx serve`
   - Using PHP: `php -S localhost:8000`

3. Open your browser and navigate to `http://localhost:8000`

## Demo site

A live demo of the application is available at https://card-trainer.netlify.app/

## License

MIT License - feel free to use this code for any purpose.
