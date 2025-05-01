# Start Page

A minimal, dark-theme new-tab start page you can host locally or publish via GitHub Pages / as a Chrome extension.

---

## Demo

Open [https://k-adm.github.io/start-page/](https://k-adm.github.io/start-page/) to see it in action.

---

## Features

- **Google-style search bar**  
  Redirects to Google in a new tab.
- **Dynamic Unsplash background**  
  Fetches a random full-HD (1920×1080) image by your search query.
- **20% black overlay**  
  Improves contrast over the background image.
- **Favorites grid**  
  Add, edit, delete your favorite sites (up to 8 per row).  
  Edits are saved in `localStorage`.
- **Customize dialog**  
  Set your Unsplash Access Key & search query at runtime.
- **White Google logo**  
  Matches Chrome’s dark-mode new-tab branding.

---

## Getting Started

### Prerequisites

- Modern browser (Chrome, Firefox, Edge…)

### Installation

```bash
git clone https://github.com/k-adm/start-page.git
cd start-page
# No build steps—just open:
open index.html
```

(Optional) To make this your default new-tab page:

- **Chrome**: Load as an unpacked extension.
- **Firefox**: Use an add-on like “Custom New Tab Page.”

---

## Usage

1. **Search**  
   - Type in the search bar and press Enter or click the 🔍 icon.  
   - Opens Google in a new tab.
2. **Manage Favorites**  
   - Click the **+** tile to add a site (name + URL).  
   - Click the pencil icon on any tile to edit or delete it.  
   - Favorites persist via `localStorage`.
3. **Customize Background**  
   - Click **Customize** in the footer.  
   - Enter your **Unsplash Access Key** and **search query**.  
   - Click **Save** to immediately update the background.

---

## Unsplash API Key

1. Go to [Unsplash Developers](https://unsplash.com/developers) and sign in.  
2. Create a new application; copy the **Access Key**.  
3. Paste it into the Customize dialog on the page.

---

## Project Structure

```
start-page/
├── index.html       ← All HTML/CSS/JS in one file
├── README.md        ← This file
└── LICENSE          ← MIT License
```

---

## Contributing

1. Fork the repo.  
2. Create a branch (`git checkout -b feature/foo`).  
3. Commit your changes (`git commit -am 'Add foo'`).  
4. Push to your branch (`git push origin feature/foo`).  
5. Open a Pull Request.

---

## License

Distributed under the MIT License. See [LICENSE](LICENSE) for details.

---

> Built and maintained by [k-adm](https://github.com/k-adm). Enjoy your personalized start page!