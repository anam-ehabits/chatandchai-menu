# Takeaway Menu Display System

A lightweight, self-hosted menu display system for 4 screens. No monthly fees. Updates automatically.

## Folder Structure

```
/
├── index.html          ← Dashboard (not shown on screens)
├── screen1/
│   ├── index.html      ← Shown on Screen 1
│   └── menu.jpg        ← Your menu image for Screen 1
├── screen2/
│   ├── index.html
│   └── menu.jpg
├── screen3/
│   ├── index.html
│   └── menu.jpg
└── screen4/
    ├── index.html
    └── menu.jpg
```

## Setup on GitHub Pages

1. Create a new GitHub repository (can be private with GitHub Pro, or public for free)
2. Upload all these files to the repository
3. Go to **Settings → Pages → Source** and select `main` branch
4. Your site will be live at `https://yourusername.github.io/your-repo-name/`

## Adding Your Menu Images

1. Design your menu as a JPG or PNG image (landscape works best)
2. Name it `menu.jpg`
3. Upload it to the correct screen folder (e.g. `screen1/menu.jpg`)
4. The screen will pick up the new image within 5 minutes automatically

## Pointing Your Screens

Open the following URLs on each TV/device browser:

- **Screen 1:** `https://yourusername.github.io/your-repo/screen1/`
- **Screen 2:** `https://yourusername.github.io/your-repo/screen2/`
- **Screen 3:** `https://yourusername.github.io/your-repo/screen3/`
- **Screen 4:** `https://yourusername.github.io/your-repo/screen4/`

Set each browser to fullscreen (F11 or the TV's fullscreen option).

## Customisation

- **Change refresh rate:** Edit `REFRESH_INTERVAL` in each screen's `index.html` (value is in milliseconds)
- **Use PNG instead of JPG:** Change `IMAGE_FILE = 'menu.jpg'` to `IMAGE_FILE = 'menu.png'`
- **Rename screens:** Edit the `<title>` and `<h1>` tags in each screen's `index.html`
