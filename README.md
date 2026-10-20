# QPTech Blog: Technology and Trends

> A dark-themed tech blog website covering Artificial Intelligence, Electric Vehicles, Automobiles, and Food & Agricultural Technology.

---

## About

QPTech Blog delivers stories, breakthroughs, and trends in AI, EVs, smart agriculture, and future technology. The site is organized into three main topic areas, each with its own page and dropdown navigation.

## Features

- **Hero section**: bold "Tech Blogging at Its Best!" intro with a featured car image and call-to-action
- **Topic sections**: Artificial Intelligence, Cars/EVs/Automotive Technology, and Food & Agricultural Technology
- **Dropdown navigation**: hover-to-open menus on desktop, tap-to-open on mobile
- **Image gallery**: asymmetric grid showcasing machine learning, EV, and agriculture visuals
- **Smooth scrolling**: animated anchor navigation and a floating back-to-top button
- **Animations**: fade and slide-in effects on page load
- **Responsive design**: layout adapts from desktop to mobile
- **Footer**: quick links, social media links, and contact information

## Pages

| Page            | Topic                                              |
| --------------- | -------------------------------------------------- |
| `index.html`    | Home and blog overview                             |
| `Trends.html`   | Latest trends, future applications, and technology |
| `cars.html`     | Latest cars and models                             |
| `evs.html`      | Technology and EVs                                 |
| `FA.html`       | Food and Agriculture: new tools, machines, tech    |
| `caddilac.html` | Cadillac                                           |
| `chevrolet.html`| Chevrolet                                          |
| `honda.html`    | Honda                                              |
| `porsche.html`  | Porsche                                            |
| `subaru.html`   | Subaru                                             |

## Tech Stack

- HTML5, CSS3, and vanilla JavaScript
- [Bootstrap 5.3.6](https://getbootstrap.com/) (via CDN)
- [Font Awesome 6.4.0](https://fontawesome.com/) (via CDN)
- [Google Fonts](https://fonts.google.com/): Inter, Roboto, Noto Sans, Lobster, Alex Brush

## Project Structure

```
cars/
├── index.html        # Home
├── Trends.html       # Latest trends
├── cars.html         # Cars and models
├── evs.html          # EVs and technology
├── FA.html           # Food and agriculture
├── caddilac.html     # Car brand pages
├── chevrolet.html
├── honda.html
├── porsche.html
├── subaru.html
├── Images/           # Site images
└── README.md
```

## Getting Started

No build step is required.

1. **Clone the repository**
   ```bash
   git clone https://github.com/HiraiGinji/cars.git
   cd cars
   ```

2. **Open the site**
   - Double-click `index.html`, **or**
   - Serve it locally:
     ```bash
     python -m http.server 8000
     ```
     Then visit `http://localhost:8000`.

> An internet connection is needed for Bootstrap, Font Awesome, and Google Fonts.

## Customization

| What to change      | Where                                                       |
| ------------------- | ----------------------------------------------------------- |
| Accent color (red)  | `#ff0000` in the `<style>` block                            |
| Hero image          | `Images/ferrariedit.png` in `.intro-section`                |
| Topic sections      | `.content-section` blocks in `index.html`                   |
| Footer links & info | The `<footer>` section in `index.html`                      |

## Author

Created by [HiraiGinji](https://github.com/HiraiGinji).
