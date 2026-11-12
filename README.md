# Noraiz Birthday Surprise 🎂

A standalone, responsive birthday-surprise website built with HTML, CSS, and JavaScript.

## Live Demo

After enabling GitHub Pages, your website will be available at:

`https://YOUR-USERNAME.github.io/YOUR-REPOSITORY/`

Replace the username and repository name with your own GitHub details.

## Features

- Animated birthday intro and notification screen
- Interactive cake with candles you can tap or blow out using a microphone
- Birthday music, voice greeting, fireworks, and confetti
- Three interactive gifts: photo memories, a personal letter, and a treat voucher
- Animated chat-style birthday messages
- Responsive layout for phones and desktop screens
- No backend, database, build process, or external library required

## Files

- `index.html` — the complete website (HTML, CSS, and JavaScript)

## Run Locally

1. Download or extract this repository.
2. Open `index.html` in a modern web browser.
3. Allow microphone access if you want to use the blow-out-the-candles feature. You can also tap the candles instead.

Some browser features, particularly microphone access, may require HTTPS or `localhost`. GitHub Pages provides HTTPS.

## Customize the Birthday Website

Open `index.html` in a code editor and find the `CONFIG` object near the beginning of the file. You can change:

- `birthday` — recipient's name
- `from` — sender's name
- `age` — age shown on the cake and finale
- `birthDate` — birthday month, day, hour, and minute (`month` uses 1–12)
- `photos` — optional image paths, for example `["photos/1.jpg", "photos/2.jpg"]`
- `captions` — captions for the photo cards
- `letter` — personal birthday letter paragraphs
- `chat` — messages shown in the chat sequence
- `voucher` — gift voucher text
- `ad` — developer promotion and contact details

To include photos in the repository, create a `photos` folder, add your images, and update the `photos` array with their relative paths. Keep file names and letter case exactly the same.

The current configuration has the birthday lock disabled (`lockUntilBirthday: false`), so the surprise can be opened at any time.

## Publish on GitHub Pages

1. Create a new repository on GitHub.
2. Extract this ZIP file on your computer.
3. Upload **the contents** of the extracted folder (especially `index.html` and `README.md`) to the repository's root. Do not upload only the ZIP file.
4. Open the repository's **Settings → Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Select the `main` branch and the `/ (root)` folder, then save.
7. Wait for GitHub Pages to finish deploying. Open the URL shown in the Pages section.

## Notes

- This is a static website; it does not need a traditional backend server.
- No installation or build command is needed.
- If you add photos or audio files, upload those assets to the repository and use correct relative paths.
- The website uses browser-native audio, speech synthesis, and microphone APIs. Availability of voices depends on the visitor's browser and device.

## License

No license is specified. Add a license file if you want to grant others explicit permission to reuse or modify the project.
