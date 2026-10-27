# LocalBazzarao

A one-stop travel booking website for **Delhi**: flights, cabs and hotels in one place, with a friendly chatbot that helps you plan.

**Live demo:** https://dimple2006sharma.github.io/localbazzarao/

> Note: this is a demo build. Prices are estimates and no real bookings or payments happen yet.

## Features

- **Login / Register** page for new and returning users
- **Chatbot** that asks simple questions (where from, where to, when, how many people) and then helps you book
- **Quick-book panel** with Flights, Hotels and Cabs icons for people who already know where they want to go
- **Explore** tab for first-time visitors: pick what you enjoy (history, food, shopping, temples, nightlife, family fun) and get place suggestions
- **3 options for every search:** Premium, Normal and Cheapest (for rides, the cheapest option uses the Delhi Metro)
- **Hotel help:** area, check-in date, nights, guests, plus the nearest metro station
- **Chotu**, a small WhatsApp-style support chat box
- Light / dark mode, animations and place cards

## Tech

Plain HTML, CSS and JavaScript in a single file. No framework, no build step, no installs.

## Run it locally

1. Download or clone this repository.
2. Open `index.html` in your browser.

For auto-refresh while editing, use the **Live Server** extension in VS Code: right-click `index.html` and choose **Open with Live Server**.

## Project structure

```
localbazzarao/
├── index.html     # the whole website
├── README.md      # this file
└── images/        # optional place photos
```

## Customize

- **WhatsApp number:** open `index.html`, search for `WA_NUMBER` and replace the value with your number in digits only, with country code (for example `91XXXXXXXXXX`).
- **Place photos:** add files to the `images` folder with these names and they will replace the drawn pictures automatically:
  `india-gate.jpg`, `red-fort.jpg`, `qutub-minar.jpg`, `lotus-temple.jpg`, `chandni-chowk.jpg`, `connaught-place.jpg`, `hauz-khas.jpg`, `akshardham.jpg`, `saket.jpg`, `cyber-hub-gurugram.jpg`
- **Name:** search for `LocalBazzarao` in `index.html`.

## Known limits (demo)

- User accounts are stored in the browser only, which is not secure for a real product.
- Prices are calculated estimates, not live data.
- The chatbot and Chotu follow fixed rules.

## Roadmap

- [ ] Real login with a backend (Firebase or Supabase)
- [ ] Live cab, hotel and flight prices through partner APIs
- [ ] Payments (Razorpay)
- [ ] AI-powered chat using the Claude API
- [ ] Map view and Hindi language option
