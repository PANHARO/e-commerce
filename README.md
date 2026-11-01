# GenZ Outlet

A static clothing storefront exercise built with HTML, Tailwind CSS, and JavaScript. Includes home, men, women, kids, about, and contact pages, with product cards and a mobile navigation menu.

## Preview

From the repository root:

```sh
python -m http.server 8000
```

Open [localhost:8000](http://localhost:8000). Use `python3` if that is your Python 3 command. The compiled stylesheet is already included; external images, Tailwind browser assets, and AOS animations require internet access.

## Edit styles

Install Node.js and npm, then run:

```sh
npm ci
npm run dev
```

The command watches `src/input.css` and writes `src/output.css`; it does not start a web server. Keep the preview server running in a separate terminal.

Edit content in the root HTML pages. Search, shopping, and contact controls are frontend demonstrations; no product API, payment service, or order backend is included.
