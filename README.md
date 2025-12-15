# Machines of Code

A living notebook on patterns, information, structure, change, and limits.

## Quick Start

### Option 1: GitHub Pages (Recommended)

1. Create a new repository on GitHub named `machines-of-code` (or `yourusername.github.io` for your main site)
2. Upload all these files to the repository
3. Go to Settings → Pages → Source → Deploy from branch (main)
4. Your site will be live at `https://yourusername.github.io/machines-of-code/`

### Option 2: Local Preview

Open `index.html` in your browser, or run a local server:

```bash
# Python 3
python -m http.server 8000

# Then visit http://localhost:8000
```

## File Structure

```
machines-of-code/
├── index.html          # Homepage
├── css/
│   └── style.css       # All styling
├── images/
│   └── logo.png        # Your logo
├── pages/
│   ├── about.html      # About page
│   ├── start-here.html # Entry point for new readers
│   ├── essays.html     # Essays listing
│   ├── problem-solving.html  # Problem breakdowns
│   └── build-notes.html      # Practical builds
└── README.md           # This file
```

## Adding New Posts

1. Create a new HTML file in `pages/` (copy an existing page as template)
2. Update the navigation links in all pages
3. Add a link to your new post in the relevant listing page

## Customization

- **Colors**: Edit CSS variables in `css/style.css` under `:root`
- **Fonts**: Change the Google Fonts import at the top of `style.css`
- **Logo**: Replace `images/logo.png` with your own

## Subscribe Form

The subscribe form currently doesn't do anything. To make it work:

1. **Substack**: Replace the form with your Substack embed
2. **Buttondown**: Use their form embed
3. **Custom**: Connect to your email service API

## Future Improvements

- [ ] Add RSS feed
- [ ] Add dark/light theme toggle
- [ ] Add search functionality
- [ ] Convert to static site generator (Jekyll/Hugo) for easier blogging

---

Built with intention. No frameworks, no complexity. Just HTML, CSS, and purpose.
