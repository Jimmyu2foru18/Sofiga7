# Sofiga7 Personal Website

A modern, interactive personal website for Sofiga7 featuring social media links, about section, and an interactive snake game. The website is built with HTML, CSS, JavaScript, and uses Tailwind CSS for styling.

## Features

- Responsive design that works on all devices
- Animated social media cards linking to Discord, YouTube, and Twitch
- Interactive snake game with increasing difficulty
- About section with personal information
- Ball python (Gimli) information section
- Modern UI with smooth animations and transitions
- Custom scrollbar design

## Technologies Used

- HTML5
- CSS3
- JavaScript
- Tailwind CSS
- SVG Icons

## Project Structure

```
├── index.html          # Main HTML file
├── styles.css          # Custom CSS styles
├── game.js             # Snake game implementation
├── discord.svg         # Discord icon
├── youtube.svg         # YouTube icon
├── twitch.svg          # Twitch icon
└── README.md           # Project documentation
```

## Deployment

To deploy this website to GitHub Pages:

1. Create a new repository on GitHub
2. Initialize Git in the project folder:
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   ```
3. Add your GitHub repository as remote:
   ```bash
   git remote add origin your-repository-url
   git branch -M main
   git push -u origin main
   ```
4. Go to your repository settings on GitHub
5. Under "Pages", select the main branch as source
6. Your site will be published at `https://your-username.github.io/repository-name`

## Local Development

To run the website locally:

1. Clone the repository
2. Open `index.html` in your web browser
3. For live reload functionality, you can use a local server like Live Server in VS Code

## Customization

The website can be customized by:

- Modifying colors in `styles.css`
- Adjusting the layout in `index.html`
- Changing game parameters in `game.js`
- Updating content in the About and Python Information sections

## Browser Support

The website is compatible with:

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## License

This project is open source and available under the MIT License.