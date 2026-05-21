# 🌤 SkyCast — Weather App

A clean, beautiful real-time weather app built with **vanilla HTML, CSS & JavaScript**, powered by the [OpenWeatherMap API](https://openweathermap.org/api).

> **First project by [@yourusername](https://github.com/yourusername)** · Built to practice API integration and frontend design.

---

## ✨ Features

- 🔍 **Search any city** in the world
- 🌡 **Current temperature** with feels-like reading
- 💧 Humidity · 💨 Wind speed · 👁 Visibility stats
- 📅 **5-day forecast** with high/low temperatures
- 🎨 **Dynamic backgrounds** that change with the weather (clear sky, rain, snow, storm…)
- 🔄 Toggle between **°C and °F**
- ✨ Animated particle star background
- 📱 Fully **responsive** — works on mobile & desktop

---

## 🖼 Preview

> *(Add a screenshot here after running the app — drag & drop an image into the GitHub editor)*

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/skycast-weather-app.git
cd skycast-weather-app
```

### 2. Get a free API key

1. Go to [openweathermap.org](https://openweathermap.org) and create a **free account**
2. Navigate to **API keys** in your profile dashboard
3. Copy your default API key (or generate a new one)
4. The free tier allows **60 calls/minute** — more than enough

### 3. Add your API key

Open `index.html` and find **line 10**:

```js
const API_KEY = 'YOUR_API_KEY_HERE';
```

Replace `YOUR_API_KEY_HERE` with your actual key:

```js
const API_KEY = 'a1b2c3d4e5f6...';
```

### 4. Open the app

Simply open `index.html` in your browser — no build tools, no npm, no server needed!

```bash
# Or use VS Code's Live Server extension for auto-reload
```

---

## 🛠 Tech Stack

| Technology | Purpose |
|---|---|
| HTML5 | Structure |
| CSS3 | Styling, animations, glassmorphism |
| Vanilla JavaScript | Logic & API calls |
| [OpenWeatherMap API](https://openweathermap.org/api) | Live weather data |
| Google Fonts (Outfit + DM Serif Display) | Typography |

---

## 📁 Project Structure

```
skycast-weather-app/
│
├── index.html        # Main app (HTML + CSS + JS in one file)
└── README.md         # You're reading this!
```

---

## 🌐 API Used

**OpenWeatherMap** — Free tier, no credit card required.

| Endpoint | Used For |
|---|---|
| `/data/2.5/weather` | Current weather |
| `/data/2.5/forecast` | 5-day / 3-hour forecast |

---

## 💡 What I Learned

- How to use `fetch()` to call a real-world REST API
- Handling JSON responses and displaying dynamic data
- CSS animations, glassmorphism, and responsive design
- Working with `async/await` and error handling
- Structuring a project for GitHub

---

## 🔮 Future Improvements

- [ ] Geolocation support (auto-detect user's city)
- [ ] Hourly forecast chart
- [ ] Sunrise & sunset times
- [ ] Dark/Light mode toggle
- [ ] PWA support (offline mode)

---

## 📄 License

This project is open source under the [MIT License](LICENSE).

---

## 🙋‍♂️ Author

**Saiman**
- GitHub: [@yourusername](https://github.com/drayvorn18)

*Feel free to star ⭐ this repo if you found it helpful!*
