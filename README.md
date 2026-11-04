# Zohaib Logistics

An immersive, single-file **3D logistics website** built with HTML, CSS, JavaScript, and [Three.js](https://threejs.org/). It presents a logistics company's services, track record, and contact channels in an interactive, visually engaging experience, with zero build tools and zero dependencies to install.

**Live Demo:** [zohaib-logistics.vercel.app](https://zohaib-logistics.vercel.app/)

---

## Features

- **Interactive 3D visuals** powered by Three.js
- **Single-file architecture:** the entire site lives in `index.html`, so it is easy to host, edit, and share
- **Config-driven content:** update company details from one place, with no code changes elsewhere
- **Smart empty fields:** any detail left blank is automatically hidden from the site
- **Lead capture ready:** connect a Google Sheets form to collect inquiries
- **Shipment tracking link** support
- **Analytics ready:** Google Analytics and Microsoft Clarity integration
- **Responsive design** for desktop and mobile

## Tech Stack

| Layer | Technology |
|-------|------------|
| Markup and Styling | HTML5, CSS3 |
| Logic | Vanilla JavaScript |
| 3D Graphics | Three.js (loaded via cdnjs.cloudflare.com) |
| Hosting | Vercel / GitHub Pages |

## Getting Started

### Run locally

1. Clone the repository:
   ```bash
   git clone https://github.com/zohaibmahar234/zohaib-logistics.git
   cd zohaib-logistics
   ```
2. Open `index.html` in your browser by double-clicking it.

> An internet connection is required on the first load, because Three.js is fetched from a CDN.

## Customization

Open `index.html` in a text editor and search for:

```js
var CFG
```

Fill in the fields you need:

| Field | Purpose |
|-------|---------|
| `address`, `hours`, `ntn` | Company details |
| `clients`, `reviews`, `cases` | Social proof and case studies |
| `schedule`, `jobs`, `brochure` | Shipping schedule, careers, downloadable brochure |
| `formUrl` | Google Sheets form for inquiries |
| `trackUrl` | Shipment tracking page |
| `gaId` | Google Analytics measurement ID |
| `clarityId` | Microsoft Clarity project ID |

Empty fields stay hidden on the site. Form and analytics integrations start working after deployment.

## Deployment

### Vercel (recommended)

1. Push this repository to GitHub.
2. Go to [vercel.com](https://vercel.com) and sign in with GitHub.
3. Click **Add New Project** and import `zohaib-logistics`.
4. Click **Deploy**.

### GitHub Pages

1. Open the repository **Settings > Pages**.
2. Under **Branch**, select `main` and `/ (root)`, then save.
3. Your site will be live in a minute or two.

## Project Structure

```
zohaib-logistics/
├── index.html    # Complete website (markup, styles, scripts)
└── README.md     # Project documentation
```

## Author

**Zohaib Mahar**
- GitHub: [@zohaibmahar234](https://github.com/zohaibmahar234)
- Portfolio: [zohaibmahar.vercel.app](https://zohaibmahar.vercel.app)

---

If you found this project useful, consider giving it a star.
