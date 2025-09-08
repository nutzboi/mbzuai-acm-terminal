# MBZUAI ACM Terminal

A beautiful, interactive terminal-themed landing page for MBZUAI ACM Student Chapter (AI + Competitive Programming).

## Features

- **Interactive Terminal Interface**: Type commands to explore the chapter
- **Multiple Themes**: Switch between green, amber, and ice themes
- **RNN Performance Demo**: Interactive neural network training simulation
- **Responsive Design**: Works on desktop and mobile devices
- **Pure JavaScript**: No build tools or Node.js required

## Available Commands

- `help` - Show available commands
- `about` - Learn about MBZUAI ACM chapter
- `events` - View upcoming activities and schedule
- `join` - How to become a member
- `links` - Discord, GitHub, and social media links
- `rnn` - Interactive RNN performance demo
- `clear` - Clear the terminal screen
- `theme` - Switch themes (green, amber, ice)

## Technology Stack

- **React 18** - Frontend framework
- **TailwindCSS** - Styling
- **Pure JavaScript** - No build tools needed
- **Local React Files** - No CDN dependencies

## Project Structure

```
├── index.html              # Main application file
├── react.development.js    # React library
├── react-dom.development.js # React DOM library
└── README.md              # This file
```

## 🚀 Quick Start

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/mbzuai-acm-terminal.git
   cd mbzuai-acm-terminal
   ```

2. **Open in browser**:
   - Simply open `index.html` in any modern web browser
   - Or serve with a local server:
     ```bash
     python3 -m http.server 8000
     # Then visit http://localhost:8000
     ```

3. **Deploy**:
   - Upload all files to any web hosting service
   - Works with GitHub Pages, Netlify, Vercel, etc.

## 🎨 Customization

### Update Links
Edit the `LINKS` object in `index.html`:
```javascript
const LINKS = {
  discord: "https://your-discord-link",
  github: "https://github.com/your-org",
  email: "mailto:your-email@university.edu",
  join: "https://your-join-form-link",
  // ... other links
};
```

### Change ASCII Art
Replace the `ASCII` constant with your own ASCII art:
```javascript
const ASCII = `
Your ASCII art here...
`;
```

### Add New Commands
Add new cases to the `handleCommand` function:
```javascript
case "yourcommand":
  push(yourCommandFunction());
  break;
```

## 🌐 Deployment

### GitHub Pages
1. Push to GitHub repository
2. Go to Settings → Pages
3. Select source branch
4. Your site will be live at `https://yourusername.github.io/repository-name`

### Netlify
1. Drag and drop the folder to netlify.com
2. Your site will be live instantly

### Vercel
1. Connect your GitHub repository to Vercel
2. Deploy with zero configuration

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📞 Contact

- **Discord**: [Join our server](https://example.com/discord)
- **Email**: acm@mbzuai.ac.ae
- **GitHub**: [@mbzuai-acm](https://github.com/mbzuai-acm)
- **Join Form**: [Membership Application](https://forms.gle/nGWaWPL7W3hQoasbA)

---

Built with ❤️ by the MBZUAI ACM web team
