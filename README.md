# Menu Website

A simple static site with a landing page linking to 3 PDF menus (Restaurant, Cafe, Beverages).

## File placement

Drop your files into these exact paths (names matter — they're referenced by [index.html](index.html)):

- `assets/logo.png` — your logo
- `menus/restaurant-menu.pdf`
- `menus/cafe-menu.pdf`
- `menus/beverages-menu.pdf`

## Run locally

Just open [index.html](index.html) in a browser, or serve it:

```bash
npx serve .
```

## Deploy to Vercel

1. Push this folder to a new GitHub repo.
2. Go to [vercel.com/new](https://vercel.com/new), import the repo.
3. Framework preset: **Other** (static site, no build step needed).
4. Deploy.
