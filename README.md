# 🏢 GMC Tax Auditor 

A lightweight, zero-dependency dashboard to verify Guwahati Municipal Corporation (GMC) property tax dues in real-time.

**Live Demo:** https://ghytax.vercel.app/

## ⚡ Tech Stack

* **Core:** HTML5 + Vanilla JavaScript (ES6)
* **Styling:** Tailwind CSS (via CDN)
* **Data Source:** Consumes the custom [GHY-Connect API](https://github.com/abhayy143/ghy-connect-api) hosted on Render.

## 🚀 Quick Start

No installation or build steps required.

**1. Clone the repo**
```
git clone https://github.com/abhayy143/ghytax
```
**2. Open the file** Double click ```index.html``` to open it in your browser.

## 🔌 How it Works

This frontend consumes the [GHY-Connect API](https://github.com/abhayy143/ghy-connect-api) (hosted on Render) to fetch live data:

```
// Endpoint
GET https://ghy-connect-api.onrender.com/verify-gmc?id={HOLDING_NUMBER}
```

*Built with ❤️ by [Abhayy](https://www.linkedin.com/in/abhayy143/)*