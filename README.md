# INFR3120 Assignment 1 - Portfolio

Live site: https://ilhammyns.github.io/portfolio/
Repository: https://github.com/ilhammyns/portfolio

## Pages
index.html (Home), about.html, projects.html, contact.html

## Responsive design (fluid layout, no Flexbox)
The layout is fluid: widths use percentages and `max-width`, and the project boxes use `float` and `clear`. Separate CSS files are loaded with `media` attributes on the link tags. I used the same screen sizes as the Week 3 lecture so the layout matches the course approach.

| File | Applies at | Why |
|------|-----------|-----|
| css/mobile.css | 480px and under | Typical phone widths; boxes stack in one column |
| css/tablet.css | 481px to 959px | Tablet range; two boxes per row |
| css/laptop.css | 960px and up | Laptops and desktops; three boxes per row |

css/base.css has no condition and loads on every screen. It holds the colors, header, footer, form, and shared styles.

## Gradients
- Linear gradient: the header, `linear-gradient(to right, dark navy, royal blue)`, in css/base.css, on all four pages.
- Angled linear gradient: the footer, `linear-gradient(135deg, royal blue, dark navy)`, in css/base.css, on all four pages.

## Colour scheme
Created with Adobe Color (Complementary rule): YOUR-ADOBE-COLOR-LINK

| Colour | Hex | Use |
|--------|-----|-----|
| Dark navy | #14213D | Text, header and footer gradients |
| Royal blue | #10288C | Header and footer gradients |
| Light blue | #CBE2FE | Page background |
| Light pink | #FFE8F0 | Hover colour on navigation links and buttons, footer links |
| Purple | #4B0090 | Project box stripe and h2/h3 headings |

The colours are CSS variables in the `:root` block at the top of css/base.css.

## Testing
- W3C HTML validator: RESULT
- W3C CSS validator: RESULT
- W3C Link Checker: RESULT
- Spell check (VS Code Code Spell Checker extension): RESULT
- WAVE accessibility: RESULT

## Credits and external code

### Course lecture material
- Separate CSS files per screen size loaded with `media` attributes, and `float`/`clear` layout, come from the INFR3120 Week 3 lecture code (responsive.html, full.css, tablet.css, smartphone.css).
- Form validation attributes (required, pattern, type="email") come from the Week 3 lecture on HTML5 forms.

### AI assistance (disclosure)
- I used Claude (an AI assistant made by Anthropic) while building this site. It helped write the starting structure of the HTML pages, base.css, the viewport CSS files, and the contact form markup.
- I typed the files in myself, tested them in a browser, and can explain how each part works.

### Other sources
- No code was copied from websites or other people.