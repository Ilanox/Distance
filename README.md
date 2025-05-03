# ✈️ Flight Distance Calculator

A simple, mobile-friendly web app that calculates the **flight (straight-line) distance** between your current location and any location shared via a **Google Maps link**.

> ✅ 100% client-side  
> ✅ No API keys required  
> ✅ Fully responsive for phones  
> ✅ No user data is stored or tracked

---

## 🌍 How to Use

1. Open the [website](https://ilanox.github.io/Distance/). 
2. Paste a full Google Maps URL (e.g. `https://www.google.com/maps/place/...`).
   - If you have a `maps.app.goo.gl` short link, open it in a browser first and copy the full URL from the address bar.
3. Click **"Calculate Distance"**.
4. The app will:
   - Request your location
   - Parse the map link
   - Show the distance in kilometers
   - Then display the location names (reverse geocoded from coordinates)

---

## 🛠️ Technologies

- HTML, CSS, JavaScript (vanilla)
- Geolocation API (for your current position)
- OpenStreetMap's Nominatim (for address lookups — no key needed)
- Works entirely in the browser — no backend

---

## 🔒 Privacy

- Your location is only used in your browser to calculate distance.
- No data is stored, tracked, or sent to any server.
- Reverse geocoding is performed via Nominatim's public API.

---

## 📡 Deployment

You can deploy this using **GitHub Pages**:

1. Push this repo to GitHub.
2. Go to **Settings → Pages**
3. Set source to `main` branch (or `docs/` folder).
4. Visit your site at `https://yourusername.github.io/your-repo-name`

---

## 📁 File Overview

| File         | Description                                |
|--------------|--------------------------------------------|
| `index.html` | Main HTML file with all logic embedded     |
| `README.md`  | Project info and usage instructions        |

---

## 💡 Example Google Maps Links

- `https://www.google.com/maps/place/Ben+Gurion+Airport/@32.000457,34.870312,17z`
- `https://www.google.com/maps?q=32.0745,34.7922`

---

## 📄 License

MIT — feel free to use, modify, or share.
