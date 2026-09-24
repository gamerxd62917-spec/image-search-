# 🖼️ Image Search API

A simple, stylish single-page web app for searching images using the **Printrest API**.

[![Open in Browser](https://img.shields.io/badge/Open-in_Browser-blue?style=for-the-badge)](https://gamerxd62917-spec.github.io/image-search-/)

---

## ✨ Features

- 🔍 **Real-time Image Search** – Fetches images instantly from the API
- 🎨 **Responsive Grid Layout** – Displays results in a clean, responsive grid
- ⚡ **Fast & Lightweight** – Single HTML file, no dependencies
- 🌙 **Modern UI** – Clean, minimal design with smooth interactions
- 🔄 **Loading & Error States** – User-friendly feedback

---

## 🚀 How to Use

### Option 1: Open Directly
Simply open [`index.html`](./index.html) in any modern web browser.

### Option 2: Run Locally
1. Clone the repository:
   ```bash
   git clone https://github.com/gamerxd62917-spec/image-search-.git
   cd image-search-
   ```
2. Open `index.html` in your browser.

Or use a local server:
```bash
python -m http.server 8000
# Then visit http://localhost:8000
```

---

## 🔌 API

This app uses the **Printrest API** endpoint:

```http
GET https://ansh-apis.is-dev.org/api/printrest?key=ansh&search={query}
```

Replace `{query}` with your search term (URL-encoded).

Example with `curl`:
```bash
curl -X GET "https://ansh-apis.is-dev.org/api/printrest?key=ansh&search=cats"
```

---

## 📁 Project Structure

```
image-search-/
├── index.html    # Main HTML file with CSS & JavaScript
└── README.md     # This file
```

---

## 💡 Customization

You can easily customize the appearance or behavior by editing `index.html`:

- Change colors in the `<style>` section
- Modify the API URL or parameters in the `fetch()` call
- Adjust grid layout (e.g., `grid-template-columns`)

---

## 📜 License

This project is open source and available under the [MIT License](LICENSE).

---

🌟 **Enjoy searching!** 🌟
