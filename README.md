# Kisan Saathi

Kisan Saathi is a browser-based farmer assistance portal built as a single-page app in `index.html`. It brings together crop-season guidance, equipment information, government scheme details, mandi pricing, multilingual content, and a lightweight farmer/admin login flow in one place.

## Highlights

- Supports English, Hindi, Kannada, and Tamil
- Includes farmer registration and login using browser storage
- Provides an admin dashboard for viewing registered users
- Shows crop guidance across Rabi, Kharif, Zaid, and Summer seasons
- Covers tractors, JCBs, and harvesters with price and rental details
- Includes quick answers for common questions on crops, loans, schemes, and mandi rates
- Uses a single-file setup, making it easy to open and test locally

## Demo Flow

1. Open `index.html` in a browser.
2. Log in with the default admin account or register as a new farmer.
3. Explore crop seasons, equipment details, schemes, and quick answers.
4. Switch languages using the header controls.

## Default Admin Account

- Email: `admin@kisan.com`
- Mobile: `9999999999`
- Password: `admin123`

## Project Structure

```text
.
|-- index.html
|-- README.md
```

## Tech Stack

- HTML5
- CSS3
- Vanilla JavaScript
- `localStorage` for user persistence
- `sessionStorage` for login session handling
- Font Awesome
- Google Fonts

## Current Behavior

- Data is stored in the browser only
- No backend, API, or database is connected
- The app can run by directly opening the HTML file
- The project is best suited for demos, prototypes, and learning

## Known Limitations

- Authentication is client-side only and not secure for production
- Some multilingual text in `index.html` appears to have encoding issues
- Market prices and scheme data are currently static
- HTML, CSS, and JavaScript are bundled into one file

## Next Improvements

- Split the app into separate HTML, CSS, and JavaScript files
- Fix text encoding for non-English content
- Add better form validation and user feedback
- Connect live agriculture, mandi, and scheme APIs
- Replace browser-only auth with a proper backend
- Improve responsive behavior and accessibility polish

## Run Locally

Open `index.html` in any modern browser such as Chrome, Edge, or Firefox.

