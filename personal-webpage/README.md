# Personal Webpage

A personal webpage built for an HTML/CSS lab. It introduces me, my hobbies (gym, boxing, football, coding, music and travel) and my weekly routine.

## Features

- Semantic HTML5: `header`, `nav`, `main`, `section`, `article`, `aside`, `footer`
- Headings, paragraphs, ordered and unordered lists, a table, an image, hyperlinks
- Blockquote, definition list, `details`/`summary`, code block and a form
- **Two CSS themes** (`css/style1.css` light, `css/style2.css` dark) with a "Switch theme" button
- Theme choice remembered with `localStorage`
- Responsive layout (flexbox and a media query for small screens)

## Project structure

```
personal-webpage/
├── index.html
├── css/
│   ├── style1.css      # light theme
│   └── style2.css      # dark theme (blue and yellow)
├── images/
│   └── me.jpg
├── .gitignore
├── LICENSE
└── README.md
```

## Run it locally

No build step or dependencies. Download or clone the repo and open `index.html` in a browser.

```bash
git clone https://github.com/<your-username>/personal-webpage.git
cd personal-webpage
# then open index.html in your browser
```

## Publish with GitHub Pages

1. Push the repo to GitHub.
2. Go to **Settings > Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/ (root)`, then save.
4. After a minute the site is live at `https://<your-username>.github.io/personal-webpage/`.

## Notes

- The contact form is for practice only. It has no backend, so nothing is sent or stored.
- The only data saved is the chosen theme, in the visitor's own browser (`localStorage`).

## Author

Szilard Csanad Szecsenyi

## License

Released under the MIT License. See [LICENSE](LICENSE).
