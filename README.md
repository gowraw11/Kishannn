# Kisan Saathi

Kisan Saathi is a single-file web portal for farmers that provides crop guidance, equipment details, scheme information, mandi prices, and a simple login and admin system in one `index.html` file.

## Features

- Multi-language interface with English, Hindi, Kannada, and Tamil options
- Farmer login and registration using browser storage
- Admin dashboard to view and manage registered users
- Seasonal crop guidance for Rabi, Kharif, Zaid, and Summer
- Farm equipment details for tractors, JCBs, and harvesters
- Government scheme and agricultural loan information
- Quick answer cards and question chips for common farmer queries
- Basic mandi price display and useful agriculture links

## Project Structure

```text
.
|-- index.html
|-- README.md
```

## How To Run

1. Open `index.html` in any modern web browser.
2. Register as a new user or log in with the admin account.

## Default Admin Login

- Email: `admin@kisan.com`
- Mobile: `9999999999`
- Password: `admin123`

## Tech Used

- HTML
- CSS
- JavaScript
- `localStorage` and `sessionStorage` for client-side data
- Font Awesome for icons
- Google Fonts for typography

## Notes

- This project stores user data in the browser only.
- No backend or database is connected.
- The app is best suited for demo, prototype, or learning purposes.

## Future Improvements

- Add a backend for secure authentication and real user management
- Connect live mandi prices and scheme APIs
- Improve form validation and error handling
- Separate HTML, CSS, and JavaScript into dedicated files
- Fix text encoding issues for some non-English content

