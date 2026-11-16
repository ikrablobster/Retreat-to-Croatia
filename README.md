# Retreat to Croatia

Landing page for a group wellness retreat in Croatia: 8-day programme, price and documents, photo gallery and contacts of the hosts. Content is in Ukrainian.

Demo: https://ikrablobster.github.io/Retreat-to-Croatia/

## Stack

HTML5, SCSS (compiled to `css/style.min.css`), jQuery, Slick (gallery slider), Magnific Popup (lightbox). Hosted on GitHub Pages.

## What was done

- Responsive layout (desktop to 320px) with a mobile burger menu.
- Photo gallery with a slider and a lightbox; 480px WebP thumbnails, full-size photos open in the lightbox.
- Semantic markup: one `h1`, sections with anchors (`#program`, `#price`, `#gallery`, `#contacts`), labelled icon links and buttons, keyboard-accessible menu (closes on `Esc` and on item click).
- Accessibility and performance: text contrast of at least 4.5:1, visible focus, `prefers-reduced-motion` support, lazy-loaded images with explicit sizes, unused libraries removed (no Swiper, noUiSlider or Font Awesome), SEO and Open Graph meta tags.
