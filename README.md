# Portfolio — Alexandre Milharado

Personal portfolio website showcasing my work and skills.

🔗 **Live site:** [Temporary]

## Tech Stack

- HTML5
- SCSS (organized with the **7-1 architecture pattern**)
- JavaScript

## SCSS Architecture (7-1 Pattern)

The stylesheets follow the 7-1 pattern: 7 folders, 1 main file that imports everything.

```
scss/
├── abstracts/   # Variables, functions, mixins, placeholders
├── base/        # Reset, typography, base element styles
├── components/  # Buttons, cards, forms, etc.
├── layout/      # Header, footer, nav, grid, sections
├── pages/       # Page-specific styles
├── themes/      # Theme/color variations (if any)
├── vendors/     # Third-party CSS overrides
└── main.scss    # Imports all of the above
```

## Features

- **Adblocker detection** — detects ad-blocking extensions, including Brave's built-in shields
- **No-JS detection** — detects when JavaScript is disabled and shows a fallback message

## Project Structure

```
├── index.html
├── scss/
└── assets/
└── README.md
```

## Author

**Alexandre Milharado**

- GitHub: [github.com/AlexandreMilharado](https://github.com/AlexandreMilharado)
- LinkedIn: [linkedin.com/in/alexandre-milharado](https://linkedin.com/in/alexandre-milharado/)
- Email: [alexandre.c.milharado@gmail.com](mailto:alexandre.c.milharado@gmail.com)

## License

This project is open source and available under the [Apache 2.0 License](LICENSE).
