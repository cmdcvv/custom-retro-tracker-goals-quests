# С-R-T goals-quests

A retro-style goals and quests tracker that runs as a static website.

## Run locally

Open `index.html` in a modern web browser. No build tools or dependencies are required.

## Features

- C-R-T arcade-inspired interface
- Goals and quests tracking
- Saves tracker data in the browser's local storage
- Responsive layout for desktop and mobile screens

## Data and fonts

Your tracker data is stored in the browser on the device where you use the app. It is not synced to GitHub or other devices. Clearing the browser's site data can remove saved progress.

The app loads its pixel fonts from Google Fonts. An internet connection is needed for those fonts; system monospace fonts are used as a fallback.

## Publish with GitHub Pages

1. Create a new repository on GitHub.
2. Upload the files and folders from this project. Keep `index.html` in the repository root.
3. Open the repository's **Settings** page, then select **Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the `main` branch and `/(root)`, then save.
6. Wait for GitHub Pages to finish publishing. The Pages screen will show the website URL.

## Project structure

```text
custom-retro-tracker goals-quests/
├── .gitignore
├── README.md
└── index.html
```

## License

No license is included. Add a license file if you want to grant others permission to reuse or modify this project.
