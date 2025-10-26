# Kanji Learning App

A simple, interactive web application for learning Japanese kanji characters. Built with vanilla HTML, CSS (Tailwind), and JavaScript - no complex frameworks required!

## Features

### 📚 Learn Kanji
- **JLPT Level Organization**: Browse kanji organized by JLPT levels (N5-N1)
- **Interactive Kanji Cards**: Click on any kanji to see detailed information
- **Comprehensive Information**: View onyomi, kunyomi, and English meanings
- **Responsive Design**: Works perfectly on desktop and mobile devices

## Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- No installation required!

### Running the App

1. **Download/Clone** this repository
2. **Open** `index.html` in your web browser
3. **Start learning** kanji immediately!

```bash
# If you have a local server (optional)
python -m http.server 8000
# Then visit http://localhost:8000
```

## Usage

### Learning Kanji
1. Select your JLPT level (N5, N4, N3, N2, N1)
2. Browse through kanji cards showing character, readings, and meanings
3. Click any kanji card to see detailed information in a modal

## Kanji Data

The app includes comprehensive kanji data for all JLPT levels:

- **N5**: 40 kanji (basic level)
- **N4**: 30 kanji (elementary level)  
- **N3**: 30 kanji (intermediate level)
- **N2**: 30 kanji (upper-intermediate level)
- **N1**: 30 kanji (advanced level)

Each kanji includes:
- Character (漢字)
- Onyomi readings (音読み)
- Kunyomi readings (訓読み)
- English meanings

## Technical Details

### Tech Stack
- **HTML5**: Semantic markup and structure
- **Tailwind CSS**: Responsive styling via CDN
- **Vanilla JavaScript**: No frameworks, pure JS for interactivity
- **No Dependencies**: Everything works offline after initial load

### Browser Compatibility
- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+

### File Structure
```
kanji_app/
├── index.html          # Main application file
└── README.md          # This file
```

## Customization

### Adding More Kanji
Edit the `kanjiData` object in `index.html` to add more kanji:

```javascript
const kanjiData = {
    'N5': [
        { 
            character: '新', 
            onyomi: ['しん'], 
            kunyomi: ['あたら', 'あら'], 
            meanings: ['new'] 
        },
        // ... more kanji
    ]
};
```

### Styling Changes
The app uses Tailwind CSS classes. You can:
- Modify colors in the Tailwind config
- Change layout by updating CSS classes
- Add custom CSS for additional styling

## Deployment

### GitHub Pages
1. Push your code to a GitHub repository
2. Go to repository Settings > Pages
3. Select source branch (usually `main`)
4. Your app will be available at `https://username.github.io/repository-name`

### Vercel
1. Install Vercel CLI: `npm i -g vercel`
2. Run `vercel` in the project directory
3. Follow the prompts to deploy

### Netlify
1. Drag and drop the `index.html` file to Netlify
2. Or connect your GitHub repository for automatic deployments

## Contributing

Feel free to contribute by:
- Adding more kanji data
- Improving the quiz algorithm
- Enhancing the UI/UX
- Adding new features (stroke order, audio, etc.)
- Fixing bugs

## License

This project is open source and available under the [MIT License](LICENSE).

## Acknowledgments

- Kanji data compiled from various JLPT study resources
- Tailwind CSS for beautiful, responsive styling
- Japanese language learning community for inspiration

---

**Happy Learning! 頑張ってください！** 🎌