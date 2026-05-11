# aravindpunnithan.github.io

Source for my personal site at **[aravindpunnithan.github.io](https://aravindpunnithan.github.io)**.

A small, hand-built page. Plain HTML and CSS.

## Structure

```
.
├── index.html      # the page
├── styles.css      # all styles
├── 404.html        # a quiet not-found page
└── README.md
```

## Run it locally

```bash
python3 -m http.server 8000
# http://localhost:8000
```

## Type

JetBrains Mono via Google Fonts. Falls back to the system monospace
if it cannot load.

## Theme

Dark by default. A small toggle in the header flips it to light, and the
choice is remembered in `localStorage`. Respects `prefers-color-scheme`
when no choice has been made.

## License

Released into the public domain. See [UNLICENSE](UNLICENSE).
