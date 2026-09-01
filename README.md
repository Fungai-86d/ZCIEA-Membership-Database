# ZCIEA Membership Database

A browser-based membership registry for the Zimbabwe Chamber of Informal Economy Associations (ZCIEA).

## Features

- **Member Registration & Management**: Capture full name, ID number, date of birth, gender, trade, territory, contact number, and photo
- **Membership Cards**: Generate and print digital ID cards with member photos, QR codes, and validity dates
- **Reports**: Gender, age, subscription status, and location analytics
- **Data Tools**: Import/export from Excel with data validation and duplicate detection
- **Outreach**: Send targeted messages to members by territory
- **Scalable**: Optimized for 20,000+ members with pagination and debounced search

## Demo

Open `index.html` in a browser, or serve the folder with any static web server. The demo login is:

- Username: `admin`
- Password: `admin123`

Data is stored in browser local storage.

## Technologies

- Vanilla JavaScript (no framework dependencies)
- SheetJS for Excel import/export
- QRCode.js for membership card QR codes
- Vercel for production deployment

## Deployment

Deploy to Vercel by connecting your GitHub repository or using the Vercel CLI.