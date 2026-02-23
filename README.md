# Bingo Generator 🎰

A simple, fun way to create and play Bingo cards directly in your browser! No downloads, no installations—just pure HTML/CSS/JavaScript running on GitHub Pages.

## Features ✨

- **Easy Card Creation**: Enter any terms you like, one per line
- **Multiple Grid Sizes**: Choose between 3x3, 4x4, or 5x5 grids
- **Free Space**: Odd-sized grids automatically include a free center space
- **Seed Function**: Generate reproducible bingo cards with the same seed—perfect for sharing!
- **Shareable URLs**: Create a unique link to share your exact bingo card with others
- **Play Mode**: Toggle between edit and play modes
- **Interactive Marking**: Click cells to mark them as you play
- **Print-Friendly**: Beautiful print layout for offline play
- **Responsive Design**: Works great on mobile, tablet, and desktop

## How to Use 📖

### Getting Started
1. Visit [Bingo Generator](https://m3koenig.github.io/bingo/) (hosted on GitHub Pages)
2. You'll start in **Edit Mode** with the sidebar visible

### Creating a Card
1. **Enter Terms**: Type any terms you want in the textarea (one per line)
2. **Choose Grid Size**: Select 3x3, 4x4, or 5x5
3. **Generate**: Click "Karte aktualisieren" to create your bingo card

### The Seed Function 🎲

This is the magic feature! The seed ensures **reproducible, shareable cards**.

- Every generated card gets a **seed** (a unique identifier)
- **Same seed + Same terms = Identical card layout** every time
- Perfect for sharing exact cards with friends

**How it works:**
1. Generate a card (a random seed is created automatically)
2. The URL updates with your seed, terms, and grid size
3. Share the URL—anyone who opens it will see the **exact same card**!
4. Click the 🎲 button to generate a random seed for a different card layout

**Under the hood:** Uses CYRB128 hashing + SFC32 pseudo-random generation for deterministic shuffling.

### Playing
1. Switch to **Play Mode** using the toggle in the top right
2. Click cards to mark them
3. Click again to unmark
4. First to get 5 in a row wins!

### Other Features
- **🔀 Shuffle**: Randomize term order and regenerate the card
- **Demo**: Load example German office-themed terms
- **🖨️ Print**: Print your card for offline play
- **Copy Link**: Share your card with a single click

## Tech Stack 🛠️

- **HTML5 + CSS3 + Vanilla JavaScript**
- **Tailwind CSS** for styling
- **GitHub Pages** for free hosting
- **No dependencies** — everything in one file!

## License 📝

**MIT License** — Free to use, modify, and share!

## Local Development 🚀

```bash
git clone https://github.com/m3koenig/bingo.git
cd bingo
# Open index.html in your browser
```

No build process needed—just open the HTML file!

## Use Cases 💡

- **Conference Bingo**: Use during meetings for fun
- **Event Bingo**: Birthday, holiday, or themed events
- **Learning Games**: Educational terms and vocabulary
- **Team Building**: Great icebreaker for groups

---

Have fun! 🎉