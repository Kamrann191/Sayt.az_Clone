# Sayt.az

Sayt.az is a static website project for a web services platform that offers website development, domain registration, and hosting services.

The project is built with HTML, CSS, JavaScript, and Tailwind CSS. It is configured for deployment on Ufazien Hosting.

## Project Structure

```text
.
├── index.html          # Main website page
├── calc.html           # Calculator page
├── script/
│   └── data.js         # Website data and JavaScript data source
├── style/
│   ├── input.css       # Tailwind input file
│   └── output.css      # Generated CSS file
├── img/                # Images, icons, and other assets
├── package.json        # Project scripts and dependencies
└── .ufazien.json       # Ufazien deployment configuration
```

## Requirements

- Node.js
- npm
- Ufazien CLI, if you want to deploy the website

## Installation

Install project dependencies:

```bash
npm install
```

## Development

Run Tailwind CSS in watch mode:

```bash
npm run tailwind
```

Then open `index.html` in your browser.

## Deployment

Deploy the website to Ufazien Hosting:

```bash
ufazienjs deploy
```

After deployment, the website will be available at:

```text
https://saytaz.ufazien.com
```

## Technologies

- HTML5
- CSS3
- JavaScript
- Tailwind CSS
- Font Awesome
- Swiper
