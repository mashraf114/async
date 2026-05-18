# 🌍 Where Am I? --- Geolocation & Async JavaScript Project

A JavaScript application that detects the user's current location using
the browser's Geolocation API, performs reverse geocoding to identify
the city and country, and dynamically renders country information using
external APIs.

---

## 🚀 Live Demo

https://mashraf114.github.io/async/

---

## 📌 Project Overview

The application:

- Gets the user's current geographic position
- Converts coordinates into a readable location
- Fetches country data from a public API
- Displays country details dynamically on the page

---

## 🧠 Concepts Practiced

- Async / Await
- Promises
- Fetch API
- Error Handling with try...catch
- Geolocation API
- Reverse Geocoding
- Working with External APIs

---

## 🛠️ Technologies Used

- HTML5
- CSS3
- Vanilla JavaScript (ES6+)
- Browser Geolocation API
- REST APIs

---

## 🌐 APIs Used

### Reverse Geocoding API

https://api.bigdatacloud.net/data/reverse-geocode-client

### REST Countries API

https://restcountries.com/

---

## ⚙️ How It Works

1.  User allows location permission.
2.  Latitude & Longitude are retrieved.
3.  Reverse geocoding identifies the country.
4.  Country data is fetched from REST Countries API.
5.  Country information is rendered on screen.

---

## 📂 Project Structure

    where-am-i/
    │
    ├── index.html
    ├── style.css
    ├── script.js
    └── README.md

---

## ▶️ Run Locally

```bash
git clone https://github.com/mashraf114/async.git
```

Open `index.html` in your browser.

---

## ⚠️ Important Notes

- Geolocation requires browser permission.
- Some browsers block location access without HTTPS.
- APIs used are public and require no authentication.

---

## 🎯 Learning Outcome

- Handling asynchronous workflows
- Chaining API requests
- Managing async errors
- Building real-world JavaScript apps

---

## 👨‍💻 Author

Mohamed Ashraf\
https://github.com/mashraf114

---

## 📜 License

Educational purposes only.
