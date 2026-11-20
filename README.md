# FitZone – Gym Membership Pricing Page

A static pricing page for a fictional gym called **FitZone**, built with plain HTML and CSS — no frameworks, no JavaScript.

Visitors can compare three membership plans side by side, see which features each plan includes, and enter a promo code.

## Preview

![FitZone pricing page](screenshot.png)

## Features

- **Three pricing cards** (Basic, Standard, Premium) laid out side by side with `float`
- **"Most Popular" badge** pinned to the top edge of the featured card using `position: absolute`
- **Included / not included features** marked with Font Awesome check and cross icons; unavailable features are faded and struck through
- **Info tooltips** on some features using the native `title` attribute
- **Fully booked plan** — the Premium button is `disabled` and shows a `not-allowed` cursor
- **Promo code form** styled with attribute selectors and custom `:focus` outlines
- Hover effects on cards, buttons, navigation and social links

## CSS Topics Practiced

| Topic | Where it is used |
|---|---|
| Attribute selectors | `[type="submit"]` for the promo code button |
| Float & overflow | Card layout, with `overflow: auto` so the parent wraps the floated cards |
| Position (relative / absolute) | "Most Popular" badge |
| Pseudo-classes & pseudo-elements | `:hover`, `:focus`, `:nth-child()`, `:last-child`, `::placeholder` |
| Cursor | `pointer` on buttons, `not-allowed` on the disabled button, `help` on info icons |
| Opacity | Unavailable features and the disabled button |
| Text styling | `text-transform`, `letter-spacing`, `line-height` (vertical centering in the navbar) |
| Lists | Feature lists and navigation without default bullets |
| Font Awesome | Logo, check/cross marks, info, tag, clock and social icons |
| CSS nesting | Styles are written with native CSS nesting |

## Built With

- HTML5
- CSS3
- [Font Awesome 7](https://fontawesome.com/)

## Getting Started

No build step is needed.

1. Clone the repository
   ```bash
   git clone https://github.com/yusif9999/html-css-cursor-properties.git
   ```
2. Open `index.html` in your browser.

## Project Structure

```
fitzone-pricing-page/
├── index.html
└── style.css
```

## Next Steps

- [ ] Make the layout responsive with media queries so the cards stack on small screens
- [ ] Add a Google Font for headings
- [ ] Use descriptive classes instead of `:nth-child()` for unavailable features

## License

This project was created for learning purposes and is free to use.
